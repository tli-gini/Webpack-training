## 安裝 node.js

## 使用 NPM 指令管理專案

1.  初始化專案：建立專案描述檔
    npm init -y

2.  安裝第三方套件

- npm install 套件名稱
- npm install 套件名稱 --save-dev

npm install webpack --save-dev
npm install webpack-cli --save-dev
一併安裝
npm install webpack webpack-cli --save-dev

3. 解除第三方套件

- npm uninstall 套件名稱

## 使用 Webpack 打包程式碼

1. Webpack 的專案結構

- src 原始程式碼的位置
- dist 目的程式碼的位置

2. 使用 Webpack 打包/建置程式碼

- npx webpack
  會打包在 main.js

  ```html
  <body>
    <script src="main.js"></script>
  </body>
  ```

- 設定 index.js 為主程式
