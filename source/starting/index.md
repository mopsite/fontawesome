---
title: 开始使用
date: 2021-10-28 19:51:40
---

如果你在一个代码库中有多个站点或应用程序，或者你想自定义 Font Awesome 的某些部分，那么自己 [下载](https://gitee.com/megaminx/asset/raw/master/fontawesome/fa-5.15.4.rar) 和托管 Font Awesome 则非常实用。

### 你的下载包含了些什么

面向 Web 的 Font Awesome 软件包包含了以下目录和文件：

|Files & Folders|What They Are|Where You Should Start|
|--|--|--|
|/css|Web 字体样式表文件|all.css|
|/js|SVG 的 JavaScript 文件|all.js|
|/less|Less 预处理器文件|fontawesome.less|
|/scss|Sass 预处理器文件|fontawesome.scss|
|/sprites|SVG 精灵图|solid.svg|
|/svgs|每个图标单独对应的 SVG|单独的 .svg 图标|
|/webfonts|样式表文件中使用的 Web 字体|参见 /css|

### 使用 Web 字体的 CSS

/css/all.css 文件包含核心样式以及使用 Font Awesome 时所需的所有图标样式。/webfonts 文件夹包含上述 CSS 引用并依赖的所有字体文件。

将整个 /webfonts 文件夹和 /css/all.css 复制到项目的静态资源目录中，然后将对 all.css 文件的引用添加到要使用 Font Awesome 的每个模板或页面的`<head>`中。

{%tabs css%}
<!-- tab 代码 -->
```html
<head>
    <link href="/your-path-to-fontawesome/css/all.css" rel="stylesheet"> <!-- 加载所有样式 -->
</head>
<body>
    <i class="fas fa-user"></i> <!-- 使用 solid 样式 -->
    <i class="far fa-user"></i> <!-- 使用 regular 样式 -->
    <i class="fal fa-user"></i> <!-- 使用 light 样式 -->
    <i class="fab fa-github-square"></i> <!-- 使用 brands 样式 -->
</body>
```
<!-- endtab -->
<!-- tab 效果 -->
<i class="fas fa-user"></i>
<i class="far fa-user"></i>
<i class="fal fa-user"></i>
<i class="fab fa-github-square"></i>
<!-- endtab -->
{%endtabs%}

### SVG 与 JavaScript 结合

/js/all.js 会加载所有基本功能，以及使用 Font Awesome 时所需的所有图标样式。将其复制到项目的静态资源目录，在要使用 Font Awesome 的每个模板或页面的`<head>`中，添加对 all.js 文件的引用。

{%tabs js%}
<!-- tab 代码 -->
```html
<head>
    <script defer src="/your-path-to-fontawesome/js/all.js"></script> <!-- 加载所有样式 -->
</head>
<body>
    <i class="fas fa-user"></i> <!-- 使用 solid 样式 -->
    <i class="far fa-user"></i> <!-- 使用 regular 样式 -->
    <i class="fal fa-user"></i> <!-- 使用 light 样式 -->
    <i class="fab fa-github-square"></i> <!-- 使用 brands 样式 -->
</body>
```
<!-- endtab -->
<!-- tab 效果 -->
<i class="fas fa-user"></i>
<i class="far fa-user"></i>
<i class="fal fa-user"></i>
<i class="fab fa-github-square"></i>
<!-- endtab -->
{%endtabs%}

### 仅使用某些样式

在将 Web 字体与 CSS 框架一起使用时，是否指向使用某些样式的图标？/css 文件夹包含 Font Awesome 所有样式（solid、regular、light 和 brands）的核心样式文件。/webfonts 文件夹包含上述 CSS 引用并依赖的所有字体文件。

|图标样式|Web 字体文件|CSS 文件|对应版本|
|--|--|--|--|
|Brands|fa-brands-400.*|brands.css|免费版|
|Solid|fa-solid-900.*|solid.css|免费版|
|Regular|fa-regular-400.*|regular.css|专业版|
|Light|fa-light-300.*|light.css|专业版|

将 /webfonts 和 /css 文件夹都复制到项目的静态资源目录中，你可以根据需要删除不打算使用的任何样式的样式表文件和 Web 字体文件。

```html
<head>
    <!-- 项目仅需要 Solid + Brands -->
    <link href="/your-path-to-fontawesome/css/fontawesome.css" rel="stylesheet">
    <link href="/your-path-to-fontawesome/css/brands.css" rel="stylesheet">
    <link href="/your-path-to-fontawesome/css/solid.css" rel="stylesheet">
</head>
<body>
    <i class="fas fa-user"></i> <!-- 使用 solid 样式 -->
    <i class="fab fa-github-square"></i> <!-- 使用 brands 样式 -->
</body>
```

在将 SVG 与 CSS 框架一起使用时，如果只想使用某些样式，方法同上。

```html
<head>
  <!-- 项目仅需要 Solid + Brands -->
  <script defer src="/your-path-to-fontawesome/js/brands.js"></script>
  <script defer src="/your-path-to-fontawesome/js/solid.js"></script>
  <script defer src="/your-path-to-fontawesome/js/fontawesome.js"></script>
</head>
<body>
  <i class="fas fa-user"></i> <!-- 使用 solid 样式 -->
  <i class="fab fa-github-square"></i> <!-- 使用 brands 样式 -->
</body>
```

{%note warning%}
建议将 /webfonts 和 /css 文件夹保留在同一目录中。因为如果不这样做，则需要更改每种样式的 CSS 文件中引用的 Web 字体的路径。
{%endnote%}

{%note info%}
如果你不想下载或不需要自定义，也可以使用 CDN 来引用。

```html 引用 CSS 文件
<link href="https://cdn.jsdelivr.net/gh/xlovet/asset/css/fontawesome/v5/all.css">
```

```html 引用 JavaScript 文件
<script src="https://cdn.jsdelivr.net/gh/xlovet/asset/js/fontawesome.js"></script>
```
{%endnote%}
