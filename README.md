# xjzbackstage

## 前言
这是在公司的后台,该项目用了的组件如下

{
  "name": "newvue",
  "version": "1.0.0",
  "description": "A Vue.js project",
  "author": "",
  "private": true,
  "scripts": {
    "dev": "webpack-dev-server --inline --progress --config build/webpack.dev.conf.js",
    "start": "npm run dev",
    "unit": "jest --config test/unit/jest.conf.js --coverage",
    "e2e": "node test/e2e/runner.js",
    "test": "npm run unit && npm run e2e",
    "lint": "eslint --ext .js,.vue src test/unit test/e2e/specs",
    "build": "node build/build.js"
  },
  "dependencies": {
    "axios": "^0.18.0",
    "axios-mock-adapter": "^1.16.0",
    "element-ui": "^2.7.2",
    "file-saver": "^2.0.1",
    "js-cookie": "^2.2.0",
    "vue": "^2.5.2",
    "vue-quill-editor": "^3.0.6",
    "vue-router": "^3.0.1",
    "vuex": "^3.1.0",
    "xlsx": "^0.14.3"
  },
  "devDependencies": {
    "autoprefixer": "^7.1.2",
    "babel-core": "^6.22.1",
    "babel-eslint": "^8.2.1",
    "babel-helper-vue-jsx-merge-props": "^2.0.3",
    "babel-jest": "^21.0.2",
    "babel-loader": "^7.1.1",
    "babel-plugin-dynamic-import-node": "^1.2.0",
    "babel-plugin-syntax-jsx": "^6.18.0",
    "babel-plugin-transform-es2015-modules-commonjs": "^6.26.0",
    "babel-plugin-transform-runtime": "^6.22.0",
    "babel-plugin-transform-vue-jsx": "^3.5.0",
    "babel-preset-env": "^1.3.2",
    "babel-preset-stage-2": "^6.22.0",
    "babel-register": "^6.22.0",
    "chalk": "^2.0.1",
    "chromedriver": "^2.27.2",
    "copy-webpack-plugin": "^4.0.1",
    "cross-spawn": "^5.0.1",
    "css-loader": "^0.28.0",
    "eslint": "^4.15.0",
    "eslint-config-standard": "^10.2.1",
    "eslint-friendly-formatter": "^3.0.0",
    "eslint-loader": "^1.7.1",
    "eslint-plugin-import": "^2.7.0",
    "eslint-plugin-node": "^5.2.0",
    "eslint-plugin-promise": "^3.4.0",
    "eslint-plugin-standard": "^3.0.1",
    "eslint-plugin-vue": "^4.0.0",
    "extract-text-webpack-plugin": "^3.0.0",
    "file-loader": "^1.1.4",
    "friendly-errors-webpack-plugin": "^1.6.1",
    "html-webpack-plugin": "^2.30.1",
    "jest": "^22.0.4",
    "jest-serializer-vue": "^0.3.0",
    "jquery": "^3.3.1",
    "mockjs": "^1.0.1-beta3",
    "nightwatch": "^0.9.12",
    "node-notifier": "^5.1.2",
    "node-sass": "^4.11.0",
    "optimize-css-assets-webpack-plugin": "^3.2.0",
    "ora": "^1.2.0",
    "portfinder": "^1.0.13",
    "postcss-import": "^11.0.0",
    "postcss-loader": "^2.0.8",
    "postcss-url": "^7.2.1",
    "rimraf": "^2.6.0",
    "sass-loader": "^7.1.0",
    "selenium-server": "^3.0.1",
    "semver": "^5.3.0",
    "shelljs": "^0.7.6",
    "style-loader": "^0.23.1",
    "uglifyjs-webpack-plugin": "^1.1.1",
    "url-loader": "^0.5.8",
    "vue-jest": "^1.0.2",
    "vue-loader": "^13.3.0",
    "vue-style-loader": "^3.0.1",
    "vue-template-compiler": "^2.5.2",
    "webpack": "^3.6.0",
    "webpack-bundle-analyzer": "^2.9.0",
    "webpack-dev-server": "^2.9.1",
    "webpack-merge": "^4.1.0"
  },
  "engines": {
    "node": ">= 6.0.0",
    "npm": ">= 3.0.0"
  },
  "browserslist": [
    "> 1%",
    "last 2 versions",
    "not ie <= 8"
  ]
}


> 另外运用了百度的富文本框ueditor外部组件

> 本人独立负责整个前端网页的制作
 
## 图片的展示

![](https://img.alicdn.com/imgextra/i2/1725217265/O1CN01emcTd823XPwXJbbIU_!!1725217265.jpg)  
![](https://img.alicdn.com/imgextra/i2/1725217265/O1CN01Kdkmh623XPwULP83D_!!1725217265.jpg)  
![](https://img.alicdn.com/imgextra/i3/1725217265/O1CN01vrGunZ23XPwVQL4EH_!!1725217265.jpg)  
