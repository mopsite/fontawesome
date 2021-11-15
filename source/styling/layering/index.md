---
title: 图标分层
date: 2021-10-29 15:53:03
---

{%note warning%}
此功能要求你使用 SVG + JS 版本的 Font Awesome。
{%endnote%}

分层是一种将图标和文本在视觉上彼此叠加的新方法，取代了传统的 [图标堆叠](../stacking)。通过这种新方法，你可以使用 2 个以上的图标。

当你不希望显示页面背景时，或者当你想使用多种颜色，在图标上分层放置多个图标或文本，或者在图标上显示计数器时，分层就非常有用。

|分层组件|使用方法|
|--|--|
|`fa-layers`|用于包装图标或文字堆叠。你可能还希望添加`fa-fw`类，以便对齐图层。|
|内部图标|直接在`fa-layers`元素内添加任意数量的图标，最后一个图标将会显示在最上层。|
|`fa-layers-text`|将文本放置在`fa-layer`元素中的最顶层图标上方。结合`data-fa-transform`可以完全控制它。|
|`fa-layers-counter`|将计数器添加到图标的右上方。可以使用`fa-layers-bottom-left`、`fa-layers-bottom-right`、`fa-layers-top-left`和默认的`fa-layers-top-right`来定位。溢出的文本将使用省略号截断。|

<div class="fa-4x">
    <span class="fa-layers fa-fw" style="background: MistyRose;">
        <i class="fas fa-circle" style="color: Tomato;"></i>
        <i class="fas fa-times fa-inverse" data-fa-transform="shrink-6"></i>
    </span>
​
    <span class="fa-layers fa-fw" style="background: MistyRose;">
        <i class="fas fa-bookmark"></i>
        <i class="fas fa-heart fa-inverse" data-fa-transform="shrink-10 up-2" style="color: Tomato"></i>
    </span>
​
    <span class="fa-layers fa-fw" style="background: MistyRose;">
        <i class="fas fa-play" data-fa-transform="rotate--90 grow-2"></i>
        <i class="fas fa-sun fa-inverse" data-fa-transform="shrink-10 up-2"></i>
        <i class="fas fa-moon fa-inverse" data-fa-transform="shrink-11 down-4.2 left-4"></i>
        <i class="fas fa-star fa-inverse" data-fa-transform="shrink-11 down-4.2 right-4"></i>
    </span>
​
    <span class="fa-layers fa-fw" style="background: MistyRose;">
        <i class="fas fa-calendar"></i>
        <span class="fa-layers-text fa-inverse" data-fa-transform="shrink-8 down-3" style="font-weight: 900;">27</span>
    </span>
​
    <span class="fa-layers fa-fw" style="background: MistyRose;">
        <i class="fas fa-certificate"></i>
        <span class="fa-layers-text fa-inverse" data-fa-transform="shrink-11.5 rotate--30" style="font-weight: 900;">NEW</span>
    </span>
​
    <span class="fa-layers fa-fw" style="background: MistyRose;">
        <i class="fas fa-envelope"></i>
        <span class="fa-layers-counter" style="background: Tomato;">1,419</span>
    </span>
</div>

```html
<div class="fa-4x">
    <span class="fa-layers fa-fw" style="background: MistyRose;">
        <i class="fas fa-circle" style="color: Tomato;"></i>
        <i class="fas fa-times fa-inverse" data-fa-transform="shrink-6"></i>
    </span>
​
    <span class="fa-layers fa-fw" style="background: MistyRose;">
        <i class="fas fa-bookmark"></i>
        <i class="fas fa-heart fa-inverse" data-fa-transform="shrink-10 up-2" style="color: Tomato"></i>
    </span>
​
    <span class="fa-layers fa-fw" style="background: MistyRose;">
        <i class="fas fa-play" data-fa-transform="rotate--90 grow-2"></i>
        <i class="fas fa-sun fa-inverse" data-fa-transform="shrink-10 up-2"></i>
        <i class="fas fa-moon fa-inverse" data-fa-transform="shrink-11 down-4.2 left-4"></i>
        <i class="fas fa-star fa-inverse" data-fa-transform="shrink-11 down-4.2 right-4"></i>
    </span>
​
    <span class="fa-layers fa-fw" style="background: MistyRose;">
        <i class="fas fa-calendar"></i>
        <span class="fa-layers-text fa-inverse" data-fa-transform="shrink-8 down-3" style="font-weight: 900;">27</span>
    </span>
​
    <span class="fa-layers fa-fw" style="background: MistyRose;">
        <i class="fas fa-certificate"></i>
        <span class="fa-layers-text fa-inverse" data-fa-transform="shrink-11.5 rotate--30" style="font-weight: 900;">NEW</span>
    </span>
​
    <span class="fa-layers fa-fw" style="background: MistyRose;">
        <i class="fas fa-envelope"></i>
        <span class="fa-layers-counter" style="background: Tomato;">1,419</span>
    </span>
</div>
```
