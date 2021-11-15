---
title: 强化变形
date: 2021-10-29 15:52:15
---

{%note warning%}
此功能要求你使用 SVG + JS 版本的 Font Awesome。
{%endnote%}

借助 Font Awesome 5 中的 SVG 强大功能，现在你可以使用`data-fa-transform`元素属性任意缩放、定位、翻转和旋转图标。你甚至可以将它们组合起来以获得一些超级有用的效果。

### 缩放比例

强化变形的缩放会影响图标大小，而无需更改或移动容器。要按比例放大或缩小图标，请使用带有任意值（包括小数）的`grow-#`和`shrink-#`。单位是 1/16em。

<div class="fa-3x">
    <i class="fas fa-seedling" data-fa-transform="shrink-8" style="background: MistyRose;"></i>
    <i class="fas fa-seedling" style="background: MistyRose;"></i>
    <i class="fas fa-seedling" data-fa-transform="grow-6" style="background: MistyRose;"></i>
</div>

```html
<div class="fa-3x">
    <i class="fas fa-seedling" data-fa-transform="shrink-8" style="background: MistyRose;"></i>
    <i class="fas fa-seedling" style="background: MistyRose;"></i>
    <i class="fas fa-seedling" data-fa-transform="grow-6" style="background: MistyRose;"></i>
</div>
```

### 定位

强化变形的位置会影响图标的位置，而无需更改或移动容器。要向上下左右移动图标，请使用`up-#`、`down-#`、`left-#`和`right-#`及其任意值，包括小数，单位是 1/16em。

<div class="fa-3x">
    <i class="fas fa-seedling" data-fa-transform="shrink-8" style="background: MistyRose;"></i>
    <i class="fas fa-seedling" data-fa-transform="shrink-8 up-6" style="background: MistyRose;"></i>
    <i class="fas fa-seedling" data-fa-transform="shrink-8 right-6" style="background: MistyRose;"></i>
    <i class="fas fa-seedling" data-fa-transform="shrink-8 down-6" style="background: MistyRose;"></i>
    <i class="fas fa-seedling" data-fa-transform="shrink-8 left-6" style="background: MistyRose;"></i>
</div>

```html
<div class="fa-3x">
    <i class="fas fa-seedling" data-fa-transform="shrink-8" style="background: MistyRose;"></i>
    <i class="fas fa-seedling" data-fa-transform="shrink-8 up-6" style="background: MistyRose;"></i>
    <i class="fas fa-seedling" data-fa-transform="shrink-8 right-6" style="background: MistyRose;"></i>
    <i class="fas fa-seedling" data-fa-transform="shrink-8 down-6" style="background: MistyRose;"></i>
    <i class="fas fa-seedling" data-fa-transform="shrink-8 left-6" style="background: MistyRose;"></i>
</div>
```

### 旋转和翻转

强化变形的旋转和翻转会影响图标的角度和反射，而无需更改或移动容器。要旋转或翻转图标，请使用带有任意值的`rotation-#`、`flip-v`和`flip-h`的任意组合。单位是允许带负数的度数。

<div class="fa-3x">
    <i class="fas fa-seedling" style="background: MistyRose;"></i>
    <i class="fas fa-seedling" data-fa-transform="rotate-90" style="background: MistyRose;"></i>
    <i class="fas fa-seedling" data-fa-transform="rotate-180" style="background: MistyRose;"></i>
    <i class="fas fa-seedling" data-fa-transform="rotate-270" style="background: MistyRose;"></i>
    <i class="fas fa-seedling" data-fa-transform="rotate-30" style="background: MistyRose;"></i>
    <i class="fas fa-seedling" data-fa-transform="rotate--30" style="background: MistyRose;"></i>
    <i class="fas fa-seedling" data-fa-transform="flip-v" style="background: MistyRose;"></i>
    <i class="fas fa-seedling" data-fa-transform="flip-h" style="background: MistyRose;"></i>
    <i class="fas fa-seedling" data-fa-transform="flip-v flip-h" style="background: MistyRose;"></i>
</div>

```html
<div class="fa-3x">
    <i class="fas fa-seedling" style="background: MistyRose;"></i>
    <i class="fas fa-seedling" data-fa-transform="rotate-90" style="background: MistyRose;"></i>
    <i class="fas fa-seedling" data-fa-transform="rotate-180" style="background: MistyRose;"></i>
    <i class="fas fa-seedling" data-fa-transform="rotate-270" style="background: MistyRose;"></i>
    <i class="fas fa-seedling" data-fa-transform="rotate-30" style="background: MistyRose;"></i>
    <i class="fas fa-seedling" data-fa-transform="rotate--30" style="background: MistyRose;"></i>
    <i class="fas fa-seedling" data-fa-transform="flip-v" style="background: MistyRose;"></i>
    <i class="fas fa-seedling" data-fa-transform="flip-h" style="background: MistyRose;"></i>
    <i class="fas fa-seedling" data-fa-transform="flip-v flip-h" style="background: MistyRose;"></i>
</div>
```
