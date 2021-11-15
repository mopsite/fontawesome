---
title: 图标堆叠
date: 2021-10-29 15:51:57
---

你可以通过 Font Awesome 附带支持样式轻松地堆叠图标。要堆叠多个图标，请在要堆叠的 2 个图标的父 HTML 元素上使用`fa-stack`类。然后为常规尺寸的图标添加`fa-stack-1x`类，为较大的图标添加`fa-stack-2x`类。

`fa-inverse`类可以与`fa-stack-1x`一起添加到图标中，以实现挖空效果。你甚至可以在父级上使用较大的图标类，以进一步控制大小。

<span class="fa-layers fa-4x">
    <i class="fas fa-square"></i>
    <i class="fab fa-twitter fa-inverse" data-fa-transform="shrink-6"></i>
</span>
<span class="fa-layers fa-4x">
    <i class="far fa-circle"></i>
    <i class="fas fa-flag" data-fa-transform="shrink-8"></i>
</span>
<span class="fa-layers fa-4x">
    <i class="fas fa-camera" data-fa-transform="shrink-6"></i>
    <i class="fal fa-ban" style="color: Tomato"></i>
</span>

```html
<span class="fa-stack fa-2x">
    <i class="fas fa-square fa-stack-2x"></i>
    <i class="fab fa-twitter fa-stack-1x fa-inverse"></i>
</span>
<span class="fa-stack fa-2x">
    <i class="far fa-circle fa-stack-2x"></i>
    <i class="fas fa-flag fa-stack-1x"></i>
</span>
<span class="fa-stack fa-2x">
    <i class="fas fa-camera fa-stack-1x"></i>
    <i class="fal fa-ban fa-stack-2x" style="color: Tomato"></i>
</span>
```
