## 使い方

このリポジトリは https://seasawher.github.io/hatenablog/ というURLでWebページとして公開されています．

CSS ファイルのパスは https://seasawher.github.io/hatenablog/style.css です．

### 手順1

```html
<link type="text/css" rel="stylesheet" href="https://seasawher.github.io/hatenablog/style.css">
```

というコードをHTMLのhead要素のところに貼り付ければ外部CSSとしての適用ができます．

### 手順２

次にCSSファイルに直接

```css
@import url("https://seasawher.github.io/hatenablog/style.css")
```

と記述してください．
