## 使い方

このリポジトリは https://seasawher.github.io/hatenablog/ というURLでWebページとして公開されています．

CSS ファイルのパスは https://seasawher.github.io/hatenablog/style.css です．

### 適用方法１

```html
<link type="text/css" rel="stylesheet" href="https://seasawher.github.io/hatenablog/style.css">
```

というコードをHTMLのhead要素のところに貼り付ければ外部CSSとしての適用ができます．

### 適用方法２

あるいは，CSSファイルに直接

```css
@import url("https://seasawher.github.io/hatenablog/style.css")
```

と記述してください．
