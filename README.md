# tinper neoui

[![npm version](https://img.shields.io/npm/v/tinper-neoui.svg)](https://www.npmjs.com/package/tinper-neoui)
[![Build Status](https://img.shields.io/travis/iuap-design/neoui/master.svg)](https://travis-ci.org/iuap-design/neoui)
[![devDependency Status](https://img.shields.io/david/dev/iuap-design/tinper-neoui.svg)](https://david-dm.org/iuap-design/tinper-neoui#info=devDependencies)
[![NPM downloads](http://img.shields.io/npm/dm/tinper-neoui.svg?style=flat)](https://npmjs.org/package/tinper-neoui)

[neoui](http://design.yyuap.com/) 是基于 `UI` 设计语言 `iUAP Design` 实现的前端框架，开放自由、易学易用、样式丰富、美观大气，为开发者提供从产品界面设计到前端开发的完整生态。

## 核心能力

### 丰富的组件

neoui 包含丰富的 CSS 组件、JS 插件

### 按需定制

可以轻松定制所需模块 减小文件尺寸 提升效率，节约资源

### 响应式布局

基于12栅格系统 全面兼容不同浏览器及设备 一次开发，多端兼容

### 完整生态

基于 neoui 扩展的各种功能插件，丰富的主题，易用的快速开发脚手架以及基于框架扩展的datatable等技术元素，为开发者提供一站式解决方案。


## 开始使用

### 获取neoui

- 直接从github获取我们的源码
```
git clone git@github.com:iuap-design/tinper-neoui.git
```

- 使用CDN
```
http://design.yyuap.com/static/uui/latest/js/u.js

http://design.yyuap.com/static/uui/latest/css/u.css
```
- 使用npm安装

```
npm install tinper-neoui
```


### 目录及文件说明

提供的资源目录结构
```
dist
│
├─css
│      font-awesome.css
│      u-core.css
│      u-core.min.css
│      u.css
│      u.min.css
│
├─fonts
│      fontawesome-webfont.eot
│      fontawesome-webfont.svg
│      fontawesome-webfont.ttf
│      fontawesome-webfont.woff
│      fontawesome-webfont.woff2
│      FontAwesome.otf
│
└─js
        neoui.js
        neoui.min.js



```

### 快速创建一个页面

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="description" content="">
  <meta name="keywords" content="">
  <meta name="viewport"
        content="width=device-width, initial-scale=1">
  <title>iUAP Design Demo</title>

  <meta name="renderer" content="webkit">
  <meta http-equiv="Cache-Control" content="no-siteapp"/>
  <meta name="mobile-web-app-capable" content="yes">
  <meta name="apple-mobile-web-app-capable" content="yes">
  <meta name="apple-mobile-web-app-status-bar-style" content="black">
  <meta name="apple-mobile-web-app-title" content="iUAP Design"/>
  <link rel="stylesheet" href="http://ddesign.yyuap.com/static/uui/latest/css/u.css">
</head>
<body>
  <h1> Hi, iUAP Design </h1>

  <!-- 你的代码 -->

  <!--[if (gte IE 9)|!(IE)]><!-->
  <script src="http://libs.baidu.com/jquery/1.11.3/jquery.min.js"></script>
  <!--<![endif]-->
  <!--[if lte IE 8 ]>
  <script src="http://cdn.staticfile.org/modernizr/2.8.3/modernizr.js"></script>
  <script src="http://design.yyuap.com/static/uui/latest/js/u-polyfill.js"></script>
  <![endif]-->
  <script src="http://design.yyuap.com/static/uui/latest/js/u-ui.js"></script>
</body>
</html>
```
### 开发文档

开发文档详见[这里](https://github.com/iuap-design/neoui/tree/master/docs)。

更多内容请移步我们的[官网](http://design.yyuap.com/)

### 6.参与讨论和开发

如在使用过程中遇到任何问题，可以在[这里](https://github.com/iuap-design/tinper-neoui/issues)提交issue反馈；

或者直接fork代码到你的github仓库，提交pull request给我们。

有紧急问题可以直接邮件给我（Email：guoyff@yonyou.com）


## 开发及构建

开发者可以一起参与为 neoui 贡献代码，同时也可以基于 neoui 进行二次开发或封装插件。

### 目录结构

```
bower.json
CHANGELOG.md
CONTRIBUTING.md
dist/
docs/
example/
fonts/
gulpfile.babel.js
js/
package.json
README.md
scss/
snippets/
vendor/
widget/
```

### 构建工具

neoui 使用 [gulp.js](http://gulpjs.com/) 构建项目。

克隆项目文件:

```
$ git clone git@github.com:iuap-design/neoui.git
```

然后进入目录安装依赖：

```
$ npm install
```

接下来，执行 `gulp`：

```
$ npm run product
```

## 反馈

[Bug 反馈及需求提交](CONTRIBUTING.md)

## 版本号
