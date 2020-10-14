# yubinbango.js を用いた郵便番号から住所の自動入力
## 使い方

- https://yubinbango.github.io/yubinbango/yubinbango.js を読み込む
- form タグに h-adr の class をつける
- form タグ内で p-country-name の class をつけたタグ内に「Japan」と入力
    - ※サンプルではこちら
    `
    <span class="p-country-name" style="display:none;">Japan</span>
    `

- 郵便番号を入力する input タグに p-postal-code の class をつける
- 住所の input タグにそれぞれの class をつける
    - 都道府県：p-region
    - 市町村区：p-locality
    - 町域：p-street-address
    - 町域以下：p-extended-address
    - まとめて表示するときは一つの input に複数の class を入れてください
