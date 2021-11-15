---
title: 样式详解
date: 2021-10-28 19:53:29
---

### 图标尺寸

图标继承了其父容器的字体大小，从而使它们可以匹配你所呈现的任何文本。通过以下类，可以相对于继承的`font-size`增大或减小图标的大小。

<div style="font-size: 0.5rem">
    <i class="fas fa-camera fa-xs"></i>
    <i class="fas fa-camera fa-sm"></i>
    <i class="fas fa-camera fa-lg"></i>
    <i class="fas fa-camera fa-2x"></i>
    <i class="fas fa-camera fa-3x"></i>
    <i class="fas fa-camera fa-5x"></i>
    <i class="fas fa-camera fa-7x"></i>
    <i class="fas fa-camera fa-10x"></i>
</div>

```html
<div style="font-size: 0.5rem">
    <i class="fas fa-camera fa-xs"></i>
    <i class="fas fa-camera fa-sm"></i>
    <i class="fas fa-camera fa-lg"></i>
    <i class="fas fa-camera fa-2x"></i>
    <i class="fas fa-camera fa-3x"></i>
    <i class="fas fa-camera fa-5x"></i>
    <i class="fas fa-camera fa-7x"></i>
    <i class="fas fa-camera fa-10x"></i>
</div>
```

通过在目标图标的项目 CSS 中、或直接在引用图标的 HTML 元素的`style`属性中设置字体大小，你还可以直接设置图标的大小。

|类名|大小|类名|大小|类名|大小|
|--|--|--|--|--|--|
|fa-xs|.75em|fa-sm|.875em|fa-lg|1.33em|
|fa-2x|2em|fa-3x|3em|fa-4x|4em|
|fa-5x|5em|fa-6x|6em|fa-7x|7em|
|fa-8x|8em|fa-9x|9em|fa-10x|10em|

### 固定宽度

是否需要垂直对齐一系列图标？例如列表或导航菜单中的图标。对于这些情况，Font Awesome 提供了固定宽度的样式。

在引用你的图标的 HTML 元素上添加`fa-fw`类，可以将一个或多个图标设置为相同的固定宽度。当更改图标宽度时（例如，宽而短的图标上方有高而瘦的图标）会使得所有图标垂直对齐，这个功能非常有用。为了清晰，下面的示例中，在图标上添加了背景色，以便你可以看到固定的宽度，还可以增大父元素的字体大小。

<div style="font-size: 1.5rem;">
    <div><i class="fas fa-skating fa-fw" style="background: DodgerBlue"></i> Skating</div>
    <div><i class="fas fa-skiing fa-fw" style="background: SkyBlue"></i> Skiing</div>
    <div><i class="fas fa-skiing-nordic fa-fw" style="background: DodgerBlue"></i> Nordic Skiing</div>
    <div><i class="fas fa-snowboarding fa-fw" style="background: SkyBlue"></i> Snowboarding</div>
    <div><i class="fas fa-snowplow fa-fw" style="background: DodgerBlue"></i> Snowplow</div>
</div>

```html
<div style="font-size: 1.5rem;">
    <div><i class="fas fa-skating fa-fw" style="background: DodgerBlue"></i> Skating</div>
    <div><i class="fas fa-skiing fa-fw" style="background: SkyBlue"></i> Skiing</div>
    <div><i class="fas fa-skiing-nordic fa-fw" style="background: DodgerBlue"></i> Nordic Skiing</div>
    <div><i class="fas fa-snowboarding fa-fw" style="background: SkyBlue"></i> Snowboarding</div>
    <div><i class="fas fa-snowplow fa-fw" style="background: DodgerBlue"></i> Snowplow</div>
</div>
```

### 列表图标

在固定宽度样式的垂直对齐基础上，Font Awesome 添加了一些实用样式，以处理带有用作装饰项目符号的图标的 HTML 列表。使用`fa-ul`和`fa-li`替换无需列表中的默认项目符号。

<ul class="fa-ul">
    <li><span class="fa-li"><i class="fas fa-check-square"></i></span>List icons can</li>
    <li><span class="fa-li"><i class="fas fa-check-square"></i></span>be used to</li>
    <li><span class="fa-li"><i class="fas fa-spinner fa-pulse"></i></span>replace bullets</li>
    <li><span class="fa-li"><i class="fas fa-square"></i></span>in lists</li>
</ul>

```html
<ul class="fa-ul">
    <li><span class="fa-li"><i class="fas fa-check-square"></i></span>List icons can</li>
    <li><span class="fa-li"><i class="fas fa-check-square"></i></span>be used to</li>
    <li><span class="fa-li"><i class="fas fa-spinner fa-pulse"></i></span>replace bullets</li>
    <li><span class="fa-li"><i class="fas fa-square"></i></span>in lists</li>
</ul>
```

### 旋转图标

有时你需要旋转、翻转或镜像图标才能在项目或设计中达到期望的效果。Font Awesome 提供了一些快速使用的工具来帮助你解决此问题。若要任意旋转或翻转图标，请在引用图标时使用`fa-rotate-*`或`fa-flip-*`类。

<div class="fa-3x">
    <i class="fas fa-snowboarding"></i>
    <i class="fas fa-snowboarding fa-rotate-90"></i>
    <i class="fas fa-snowboarding fa-rotate-180"></i>
    <i class="fas fa-snowboarding fa-rotate-270"></i>
    <i class="fas fa-snowboarding fa-flip-horizontal"></i>
    <i class="fas fa-snowboarding fa-flip-vertical"></i>
    <i class="fas fa-snowboarding fa-flip-both"></i>
</div>

```html
<div class="fa-3x">
    <i class="fas fa-snowboarding"></i>
    <i class="fas fa-snowboarding fa-rotate-90"></i>
    <i class="fas fa-snowboarding fa-rotate-180"></i>
    <i class="fas fa-snowboarding fa-rotate-270"></i>
    <i class="fas fa-snowboarding fa-flip-horizontal"></i>
    <i class="fas fa-snowboarding fa-flip-vertical"></i>
    <i class="fas fa-snowboarding fa-flip-both"></i>
</div>
```

### 图标动画

需要旋转加载或状态通信图标吗？Font Awesome 在支持样式中包括了一些基本的动画供你使用。使用`fa-spin`类可以让任意图标旋转，或者使用`fa-pulse`使其进行 8 方向旋转。特别适用于`fa-spinner`和旋转图标类别中的所有内容。

<div class="fa-3x">
    <i class="fas fa-spinner fa-spin"></i>
    <i class="fas fa-circle-notch fa-spin"></i>
    <i class="fas fa-sync fa-spin"></i>
    <i class="fas fa-cog fa-spin"></i>
    <i class="fas fa-spinner fa-pulse"></i>
    <i class="fas fa-stroopwafel fa-spin"></i>
</div>

```html
<div class="fa-3x">
    <i class="fas fa-spinner fa-spin"></i>
    <i class="fas fa-circle-notch fa-spin"></i>
    <i class="fas fa-sync fa-spin"></i>
    <i class="fas fa-cog fa-spin"></i>
    <i class="fas fa-spinner fa-pulse"></i>
    <i class="fas fa-stroopwafel fa-spin"></i>
</div>
```

Font Awesome 一直在努力使图标或搏动时保持完美居中，但是一些浏览器和 Web 字体 + Font Awesome 的 CSS 版本存在问题。这似乎是 Web 字体的普遍问题，而不是 Font Awesome 可以直接解决的。有几种方法可以解决此问题：

- 切换框架。切换到带有 JavaScript 版本的 SVG，这样做效果更好。
- 设置动画图标的显示。使用`display: block;`，这似乎对解决此问题有很大帮助。
