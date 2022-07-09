# hatenablog

このリポジトリは https://seasawher.github.io/hatenablog/ というURLでWebページとして公開されています．

CSS ファイルのパスは https://seasawher.github.io/hatenablog/style.css です．

## 手順

CSSを適用するには

```html
<link type="text/css" rel="stylesheet" href="https://seasawher.github.io/hatenablog/style.css">
```

というコードをHTMLのhead要素のところに貼り付けます．

## 補足

CSSファイルに直接

```css
@import url("https://seasawher.github.io/hatenablog/style.css")
```

と記述してもうまくいきません．

* 参考: https://minebox.hateblo.jp/entry/2018/09/08/232217


## スタイルが更新されないとき

`F12` キーを押すなどしてブラウザの開発者ツールを開いてください．

そして更新ボタンを右クリックして，キャッシュを消去してください．



