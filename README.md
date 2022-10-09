# rubi-view（ルビ対応プレビュー）

n-fukuju氏の「[縦書きプレビュー](https://marketplace.visualstudio.com/items?itemName=n-fukuju.vertical-writing)」を改変したもの
- 数行書き換えただけのため、不要な変数や処理などが残ったまま動いています。動作が不安定かもしれません。


## 改変箇所
- ルビ記号に対応
    - `|文字《ルビ》`, `｜文字《ルビ》`, `[[rb: 漢字 > ルビ]]`
- 縦書き・横書きの切替設定を追加(`rubi-view.preview.mode`)
- フォントウェイトの設定を追加(`rubi-view.preview.fontweight`)
- 「エディター中のカーソルをプレビュー画面にも表示する機能」を削除
    - ルビ表示に対応した結果、見えない字が存在することになり、カーソル位置が合わなくなりました……