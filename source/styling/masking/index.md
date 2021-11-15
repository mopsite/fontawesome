---
title: 图标遮罩
date: 2021-10-29 15:52:37
---

{%note warning%}
此功能要求你使用 SVG + JS 版本的 Font Awesome。
{%endnote%}

借助 Font Awesome 5 中 SVG 的强大功能，将两个图标结合起来可以创建一种单色形状！将其与 [强化变形](../transforms) 结合使用可以产生一些非常棒的效果。当你想要显示背景色时，遮罩非常有用。

|遮罩组件|使用方法|
|--|--|
|内部图标（空心）|使用 class 属性设置图标名称，然后使用任意`data-fa-transform`属性进行变化。|
|外部图标（遮罩）|使用内部图标上的`data-fa-mask`属性设置用作遮罩的图标名称。|

<div class="fa-4x">
    <i class="fas fa-pencil-alt" data-fa-transform="shrink-10 up-.5" data-fa-mask="fas fa-comment" style="background: MistyRose;"></i>
    <i class="fab fa-facebook-f" data-fa-transform="shrink-3.5 down-1.6 right-1.25" data-fa-mask="fas fa-circle" style="background: MistyRose;"></i>
    <i class="fas fa-headphones" data-fa-transform="shrink-6" data-fa-mask="fas fa-square" style="background: MistyRose;"></i>
    <i class="fas fa-mask" data-fa-transform="shrink-3 up-1" data-fa-mask="fas fa-circle" style="background: MistyRose;"></i>
</div>

```html
<div class="fa-4x">
    <i class="fas fa-pencil-alt" data-fa-transform="shrink-10 up-.5" data-fa-mask="fas fa-comment" style="background: MistyRose;"></i>
    <i class="fab fa-facebook-f" data-fa-transform="shrink-3.5 down-1.6 right-1.25" data-fa-mask="fas fa-circle" style="background: MistyRose;"></i>
    <i class="fas fa-headphones" data-fa-transform="shrink-6" data-fa-mask="fas fa-square" style="background: MistyRose;"></i>
    <i class="fas fa-mask" data-fa-transform="shrink-3 up-1" data-fa-mask="fas fa-circle" style="background: MistyRose;"></i>
</div>
```

