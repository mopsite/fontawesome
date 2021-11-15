---
title: 双色图标
date: 2021-10-29 15:53:21
---

双色图标就像我们所有其他图标一样使用。最重要的是，它提供了 Font Awesome 中每个图标的双色版本，该图标具有两种不同的颜色。它们非常适合为你项目中的图标添加更多品牌或插画品质。

### 基本用法

双色图标使用与其他图标相同的语法，并且可以使用其特定前缀（fad）像其他任何图标一样引用。

<div class="fa-3x">
    <i class="fad fa-camera"></i>
    <i class="fad fa-fire-alt"></i>
    <i class="fad fa-bus-alt"></i>
    <i class="fad fa-fill-drip"></i>
</div>

```html
<div class="fa-3x">
    <i class="fad fa-camera"></i>
    <i class="fad fa-fire-alt"></i>
    <i class="fad fa-bus-alt"></i>
    <i class="fad fa-fill-drip"></i>
</div>
```

### 交换图层透明度

你可以交换每个双色图标图层的默认透明度。这将使图标的主要层的默认不透明度变为 40%。

<div class="fa-3x">
    <i class="fad fa-camera fa-swap-opacity"></i>
    <i class="fad fa-fire-alt fa-swap-opacity"></i>
    <i class="fad fa-bus-alt fa-swap-opacity"></i>
    <i class="fad fa-fill-drip fa-swap-opacity"></i>
</div>

```html
<div class="fa-3x">
    <i class="fad fa-camera fa-swap-opacity"></i>
    <i class="fad fa-fire-alt fa-swap-opacity"></i>
    <i class="fad fa-bus-alt fa-swap-opacity"></i>
    <i class="fad fa-fill-drip fa-swap-opacity"></i>
</div>
```

{%btn demo/01, 更多示例 >>%}

### 改变透明度

默认情况下，双色图标中的辅助图层设为 40% 不透明度（通过 Font Awesome 支持 CSS 规则`opacity: 0.4;`）。你可以使用下面的 CSS 自定义属性来明确设置双色图标图层的透明度。

|样式属性|描述|可用值|
|--|--|--|
|--fa-primary-opacity|设置主要图层透明度|0 ~ 1.0|
|--fa-secondary-opacity|设置次要图层透明度|0 ~ 1.0|

<div class="fa-3x">
    <i class="fad fa-bus-alt" style="--fa-primary-opacity: 0.2;"></i>
    <i class="fad fa-bus-alt" style="--fa-primary-opacity: 0.4;"></i>
    <i class="fad fa-bus-alt" style="--fa-primary-opacity: 0.6;"></i>
    <i class="fad fa-bus-alt" style="--fa-primary-opacity: 0.8;"></i>
    <i class="fad fa-bus-alt" style="--fa-primary-opacity: 1.0;"></i>
</div>

```html
<div class="fa-3x">
    <i class="fad fa-bus-alt" style="--fa-primary-opacity: 0.2;"></i>
    <i class="fad fa-bus-alt" style="--fa-primary-opacity: 0.4;"></i>
    <i class="fad fa-bus-alt" style="--fa-primary-opacity: 0.6;"></i>
    <i class="fad fa-bus-alt" style="--fa-primary-opacity: 0.8;"></i>
    <i class="fad fa-bus-alt" style="--fa-primary-opacity: 1.0;"></i>
</div>
```

<div class="fa-3x">
    <i class="fad fa-bus-alt" style="--fa-secondary-opacity: 0.2;"></i>
    <i class="fad fa-bus-alt" style="--fa-secondary-opacity: 0.4;"></i>
    <i class="fad fa-bus-alt" style="--fa-secondary-opacity: 0.6;"></i>
    <i class="fad fa-bus-alt" style="--fa-secondary-opacity: 0.8;"></i>
    <i class="fad fa-bus-alt" style="--fa-secondary-opacity: 1.0;"></i>
</div>

```html
<div class="fa-3x">
    <i class="fad fa-bus-alt" style="--fa-secondary-opacity: 0.2;"></i>
    <i class="fad fa-bus-alt" style="--fa-secondary-opacity: 0.4;"></i>
    <i class="fad fa-bus-alt" style="--fa-secondary-opacity: 0.6;"></i>
    <i class="fad fa-bus-alt" style="--fa-secondary-opacity: 0.8;"></i>
    <i class="fad fa-bus-alt" style="--fa-secondary-opacity: 1.0;"></i>
</div>
```

{%btn demo/02, 更多示例 >>%}

### 为双色图标着色

像所有其他 Font Awesome 图标一样，双色图标会自动继承 CSS 大小和颜色。双色图标有主要图层和次要图层组成。默认情况下，次要图层的不透明度为 40%，因此它会以浅色显示。

|样式属性|描述|可用值|
|--|--|--|
|--fa-primary-color|设置主要图层颜色|任何 CSS 颜色值|
|--fa-secondary-color|设置次要图层颜色|任何 CSS 颜色值|

<div class="fa-3x">
    <i class="fad fa-bus-alt" style="--fa-primary-color: gold;"></i>
    <i class="fad fa-bus-alt" style="--fa-primary-color: orangered;"></i>
    <i class="fad fa-fill-drip" style="--fa-secondary-color: limegreen;"></i>
    <i class="fad fa-fill-drip" style="--fa-secondary-color: rebeccapurple;"></i>
    <i class="fad fa-battery-full" style="--fa-primary-color: limegreen; --fa-secondary-color: dimgray;"></i>
    <i class="fad fa-battery-quarter" style="--fa-primary-color: orange; --fa-secondary-color: dimgray;"></i>
</div>

```html
<div class="fa-3x">
    <i class="fad fa-bus-alt" style="--fa-primary-color: gold;"></i>
    <i class="fad fa-bus-alt" style="--fa-primary-color: orangered;"></i>
    <i class="fad fa-fill-drip" style="--fa-secondary-color: limegreen;"></i>
    <i class="fad fa-fill-drip" style="--fa-secondary-color: rebeccapurple;"></i>
    <i class="fad fa-battery-full" style="--fa-primary-color: limegreen; --fa-secondary-color: dimgray;"></i>
    <i class="fad fa-battery-quarter" style="--fa-primary-color: orange; --fa-secondary-color: dimgray;"></i>
</div>
```

{%btn demo/03, 更多示例 >>%}

### 进阶使用

当你将所有的着色、不透明度和其他选项组合在一起时，Font Awesome 图标将变得更赞。这里有一些想法关于如何使用双色图标将你的项目提升到一个新的水平。

**使用颜色突出图标的一部分或注释状态：**

<div class="fa-3x">
    <i class="fad fa-book" style="--fa-primary-color: lightseagreen; --fa-secondary-color: linen; --fa-secondary-opacity: 1.0;"></i>
    <i class="fad fa-book-spells" style="--fa-primary-color: mediumpurple; --fa-secondary-color: linen; --fa-secondary-opacity: 1.0;"></i>
    <i class="fad fa-book-medical" style="--fa-primary-color: crimson; --fa-secondary-color: linen; --fa-secondary-opacity: 1.0;"></i>
    <i class="fad fa-book-user" style="--fa-primary-color: peru; --fa-secondary-color: linen; --fa-secondary-opacity: 1.0;"></i>
    <i class="fad fa-toggle-off" style="--fa-primary-color: white; --fa-secondary-color: gray; --fa-secondary-opacity: 1.0;"></i>
    <i class="fad fa-toggle-on" style="--fa-primary-color: dodgerblue; --fa-secondary-color: white; --fa-secondary-opacity: 1.0;"></i>
    <i class="fad fa-file-plus" style="--fa-primary-color: white; --fa-secondary-color: limegreen; --fa-secondary-opacity: 1.0;"></i>
    <i class="fad fa-file-exclamation" style="--fa-primary-color: white; --fa-secondary-color: gold; --fa-secondary-opacity: 1.0;"></i>
    <i class="fad fa-file-times" style="--fa-primary-color: white; --fa-secondary-color: tomato; --fa-secondary-opacity: 1.0;"></i>
</div>

```html
<div class="fa-3x">
    <i class="fad fa-book" style="--fa-primary-color: lightseagreen; --fa-secondary-color: linen; --fa-secondary-opacity: 1.0;"></i>
    <i class="fad fa-book-spells" style="--fa-primary-color: mediumpurple; --fa-secondary-color: linen; --fa-secondary-opacity: 1.0;"></i>
    <i class="fad fa-book-medical" style="--fa-primary-color: crimson; --fa-secondary-color: linen; --fa-secondary-opacity: 1.0;"></i>
    <i class="fad fa-book-user" style="--fa-primary-color: peru; --fa-secondary-color: linen; --fa-secondary-opacity: 1.0;"></i>
    <i class="fad fa-toggle-off" style="--fa-primary-color: white; --fa-secondary-color: gray; --fa-secondary-opacity: 1.0;"></i>
    <i class="fad fa-toggle-on" style="--fa-primary-color: dodgerblue; --fa-secondary-color: white; --fa-secondary-opacity: 1.0;"></i>
    <i class="fad fa-file-plus" style="--fa-primary-color: white; --fa-secondary-color: limegreen; --fa-secondary-opacity: 1.0;"></i>
    <i class="fad fa-file-exclamation" style="--fa-primary-color: white; --fa-secondary-color: gold; --fa-secondary-opacity: 1.0;"></i>
    <i class="fad fa-file-times" style="--fa-primary-color: white; --fa-secondary-color: tomato; --fa-secondary-opacity: 1.0;"></i>
</div>
```

**创建看起来像插图的全彩图标：**

<div class="fa-3x">
    <i class="fad fa-crow" style="--fa-secondary-opacity: 1.0; --fa-primary-color: dodgerblue; --fa-secondary-color: gold;"></i>
    <i class="fad fa-campfire" style="--fa-secondary-opacity: 1.0; --fa-primary-color: sienna; --fa-secondary-color: red;"></i>
    <i class="fad fa-birthday-cake" style="--fa-secondary-opacity: 1.0; --fa-primary-color: pink; --fa-secondary-color: palevioletred;"></i>
    <i class="fad fa-ear" style="--fa-secondary-opacity: 1.0; --fa-primary-color: sandybrown; --fa-secondary-color: bisque;"></i>
    <i class="fad fa-corn" style="--fa-secondary-opacity: 1.0; --fa-primary-color: mediumseagreen; --fa-secondary-color: gold;"></i>
    <i class="fad fa-cookie-bite" style="--fa-secondary-opacity: 1.0; --fa-primary-color: saddlebrown; --fa-secondary-color: burlywood;"></i>
</div>

```html
<div class="fa-3x">
    <i class="fad fa-crow" style="--fa-secondary-opacity: 1.0; --fa-primary-color: dodgerblue; --fa-secondary-color: gold;"></i>
    <i class="fad fa-campfire" style="--fa-secondary-opacity: 1.0; --fa-primary-color: sienna; --fa-secondary-color: red;"></i>
    <i class="fad fa-birthday-cake" style="--fa-secondary-opacity: 1.0; --fa-primary-color: pink; --fa-secondary-color: palevioletred;"></i>
    <i class="fad fa-ear" style="--fa-secondary-opacity: 1.0; --fa-primary-color: sandybrown; --fa-secondary-color: bisque;"></i>
    <i class="fad fa-corn" style="--fa-secondary-opacity: 1.0; --fa-primary-color: mediumseagreen; --fa-secondary-color: gold;"></i>
    <i class="fad fa-cookie-bite" style="--fa-secondary-opacity: 1.0; --fa-primary-color: saddlebrown; --fa-secondary-color: burlywood;"></i>
</div>
```

{%btn demo/04, 更多示例 >>%}

<p></p>

**带有品牌视觉色彩的主题图标：**

<div class="fa-3x">
    <style scoped>
        .theme-ravenclaw {
            --fa-secondary-opacity: 1.0;
            --fa-primary-color: rgb(4, 56, 161);
            --fa-secondary-color: rgb(108, 108, 108);
        }
    </style>
    <i class="fad fa-hat-wizard theme-ravenclaw"></i>
    <i class="fad fa-flask-potion theme-ravenclaw"></i>
    <i class="fad fa-wand-magic theme-ravenclaw"></i>
    <i class="fad fa-scarf theme-ravenclaw"></i>
    <i class="fad fa-book-spells theme-ravenclaw"></i>
</div>

```html
<div class="fa-3x">
    <style scoped>
        .theme-ravenclaw {
            --fa-secondary-opacity: 1.0;
            --fa-primary-color: rgb(4, 56, 161);
            --fa-secondary-color: rgb(108, 108, 108);
        }
    </style>
    <i class="fad fa-hat-wizard theme-ravenclaw"></i>
    <i class="fad fa-flask-potion theme-ravenclaw"></i>
    <i class="fad fa-wand-magic theme-ravenclaw"></i>
    <i class="fad fa-scarf theme-ravenclaw"></i>
    <i class="fad fa-book-spells theme-ravenclaw"></i>
</div>
```

<div class="fa-3x">
    <style scoped>
        .holiday {
            --fa-primary-color: green;
            --fa-secondary-color: red;
        }
    </style>
    <i class="fad fa-holly-berry holiday"></i>
    <i class="fad fa-wreath holiday"></i>
    <i class="fad fa-candy-cane holiday"></i>
</div>

```html
<div class="fa-3x">
    <style scoped>
        .holiday {
            --fa-primary-color: green;
            --fa-secondary-color: red;
        }
    </style>
    <i class="fad fa-holly-berry holiday"></i>
    <i class="fad fa-wreath holiday"></i>
    <i class="fad fa-candy-cane holiday"></i>
</div>
```


{%note warning%}
由于双色图标在视觉上更为复杂，因此在较小的尺寸下可能更难读取。fa-2x 是一个很好的起点。
{%endnote%}

{%note danger%}
双色图标在所有现代 Web 浏览器中都非常出色。由于 IE（10 和 11）不支持 CSS 自定义属性，因此，虽然双色图标仍可以在该浏览器中显示，但是你无法定义各个图层的颜色或透明度。
{%endnote%}
