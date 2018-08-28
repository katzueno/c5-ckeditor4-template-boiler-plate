# c5-ckeditor4-template-boiler-plate
concrete5 CKEditor Boiler Plate

## 使い方

- /application/bootstrap/app.php を concrete5 に差し替え。
    - **注意!** も既に何か記述がある方は GitHub 上のファイル 2〜23行目を追加して下さい。
        - 2~3行目の [use ---- ] は PHP ファイルの冒頭で宣言しないといけないので気をつけて下さい。
- /application/js/ckeditor4/vendor/plugins/templates/templates/default.js
の中に HTML のテンプレートを追加。各項目に必要事項を記入して HTML にテンプレートを流し込んで下さい。
    - 入れる要素
        - title
        - image
        - description
        - HTML
- 選択画面で参考画像を表示します。その画像は `/application/js/ckeditor4/vendor/plugins/templates/templates/images` フォルダ配下に設置して下さい
- 以上のファイルを concrete5 にアップロードします。
- concrete5 に管理権限のあるユーザーでログインします。
- 管理画面 - システムと設定 - 基本 - 記事ブロックエディター設定 ページに訪問します
- エディタープラグインから、「テンプレート (Templates)」をチェックします
