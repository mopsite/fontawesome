---
title: 基本用法
date: 2021-10-28 19:52:01
---

你可以使用样式前缀和图标名称将 Font Awesome 图标放置在几乎任何地方。

Font Awesome 旨在与内联元素一起使用，建议使用一致的 HTML 元素。`<i>`标签简洁，但是`<span>`在语义上更准确。你需要知道以下两点才能引用一个图标：

1. 要使用的相应的样式前缀。
2. 以`fa-`为前缀的图标名称；

```html
<i class="fas fa-camera"></i>
<!-- 这个图标的样式前缀是 fas，图标名称是 camera -->
<i class="fas fa-camera"></i>
<!-- 使用 i 元素引用图标 -->
<span class="fas fa-camera"></span>
<!-- 使用 span 元素引用图标 -->
```

|样式|版本|样式前缀|效果|代码|
|--|--|--|--|---|
|Solid|免费版|fas|<i class="fas fa-camera">|`<i class="fas fa-camera">`|
|Regular|专业版|far|<i class="far fa-camera">|`<i class="far fa-camera">`|
|Light|专业版|fal|<i class="fal fa-camera">|`<i class="fal fa-camera">`|
|Duotone|专业版|fad|<i class="fad fa-camera">|`<i class="fad fa-camera">`|
|Brands|免费版|fab|<i class="fab fa-font-awesome">|`<i class="fab fa-font-awesome">`|

{%note info no-icon%}
`fa`样式前缀在 5.x 版本中已弃用。新的默认设置是 Solid 的 fas 样式前缀或 Brands 的 fab 样式前缀。
{%endnote%}

Font Awesome 图标会自动继承 CSS 大小和颜色。这意味着无论你将它们放在何处，它们都与内联样式混合在一起。Font Awesome 会尽量不增加复杂的设置，只在上下文中正确呈现基本样式规则。

<span style="font-size: 3em; color: Tomato;">
    <i class="fas fa-camera"></i>
</span>
<span style="font-size: 48px; color: Dodgerblue;">
    <i class="fas fa-camera"></i>
</span>
<span style="font-size: 3rem;">
    <span style="color: Mediumslateblue;">
        <i class="fas fa-camera"></i>
    </span>
</span>

```html
<span style="font-size: 3em; color: Tomato;">
    <i class="fas fa-camera"></i>
</span>
​
<span style="font-size: 48px; color: Dodgerblue;">
    <i class="fas fa-camera"></i>
</span>
​
<span style="font-size: 3rem;">
    <span style="color: Mediumslateblue;">
        <i class="fas fa-camera"></i>
    </span>
</span>
```

你还可以通过在项目代码中添加自己的 CSS 规则，将自己的自定义样式添加到 Font Awesome 图标中。下面是一个简单的例子：

```html
<head>
    <!-- 从 CDN 或你自己下载的文件中引用 Font Awesome -->
    <link href="/your-path-to-fontawesome/css/fontawesome.css" rel="stylesheet">
    <link href="/your-path-to-fontawesome/css/brands.css" rel="stylesheet">
    <link href="/your-path-to-fontawesome/css/solid.css" rel="stylesheet">
    <style>
        /* 自定义所有图标样式 */
        i.fas,
        i.fab {
            border: 1px solid red;
        }
​
        /* 自定义特殊图标样式 */
        .fa-fish {
            color: salmon;
        }
​
        .fa-frog {
            color: green;
        }
​
        .fa-user-ninja.vanished {
            opacity: 0.0;
        }
​
        .fa-facebook {
            color: rgb(59, 91, 152);
        }
    </style>
</head>
<body>
    <i class="fas fa-fish"></i>
    <i class="fas fa-frog"></i>
    <i class="fas fa-user-ninja vanished"></i>
    <i class="fab fa-facebook"></i>
</body>
```
