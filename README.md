## ArtDialog2
---
An [artDialog](https://github.com/aui/artDialog) wapper for webpack.

### 准备工作

1. 请确保您的 webpack 使用了 [css-loader](https://github.com/webpack/css-loader)

### 使用方法

1. `npm install artdialog2 --save`；
2. 引入 css，在您的样式文件中，加入 `@import "~artdialog2/css/ui-dialog.css";`；
3. 引入默认的 js 文件，`const $dialog = require('artdialog2')`，如果需要 iframe 等支持需要使用 artdialog-plus，请使用 `const $dialog = require('artdialog2/src/plus')`。

### TODO
1. 更好的修改 artdialog 配置文件的方式待完成