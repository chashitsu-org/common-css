Chashitsu Common CSS (CCCSS)
====================

Chashitsu Common CSS (CCCSS) は、複雑なレイアウトを持たないHTMLページを低コストで整形するスタイルシート（予定地）です。

Markdownで書かれた文章をHTMLに変換した時に、見た目がきれいになるのを目標にしています。ですので、`<section>` 要素や `<div>` 要素でコンテンツがラップされていなくても、違和感なく見られるものを想定しています。（もちろん、それらが入っていてもきれいに見せたいところです。）

## ビルド
node/npm が必要です。
``` sh
$ npm i
$ npm run build
```
で `dist/` 下にCSSが生成されます。

## サンプルを動作させる
node/npm が必要です。
``` sh
$ npm i
$ npm start
```
でブラウザが立ち上がります。

## ライセンス
[CC0-1.0](https://creativecommons.org/publicdomain/zero/1.0/deed.ja)
