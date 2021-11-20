---
title: Weather Icons
date: 2021-11-01 20:28:12
---

<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/xlovet/asset/css/weather-icons/main.css">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/xlovet/asset/css/weather-icons/wind.css">
<script src="https://cdn.jsdelivr.net/gh/xlovet/asset/js/clipboard.js"></script>
<script>
  var clipboard = new ClipboardJS('.wi');
</script>

<style>
  .wi {
    font-size: 2rem;
    cursor: pointer;
  }
</style>

Weather Icons 是唯一一款带有 222 个以天气为主题的图标字体库，可以直接放入任何需要高质量天气海事和气象图标的项目中。

- 灵活的 CSS
  你可以对文本进行操作，也可以对图标进行操作。缩放、旋转、翻转、更改颜色、添加阴影……等等。

- 在图形应用程序中使用
  你可以复制图标，并将其直接粘贴到 PhotoShop、Illustrator、Sketch 等图形应用程序中。

- 翻转、缩放、变换
  使用固定宽度、水平或垂直翻转和旋转 90、180 或 270 度的内置使用程序类，可以轻松修改图标外观。

- 专业图标
  222 个以天气为主题的图标，其中包括 28 个月相、12 小时的时钟、海上风向警告等。

- 支持 Less 和 Sass
  你可以使用 Less 或 Sass 预处理程序，将 Weather Icons 图标直接集成到你现有的项目中。

### 使用

要使用 Weather Icons，请将 [css 主文件](https://cdn.jsdelivr.net/gh/xlovet/asset/css/weather-icons/main.css) 放置在 css 目录中，并将 [字体文件](https://cdn.jsdelivr.net/gh/xlovet/asset/css/weather-icons/font/weathericons-regular-webfont.woff2) 放置在与 css 目录相同文件夹级别的 font 目录中。完成此操作后，在 HTML 中引用图标所要做的就是`<i class="wi wi-night-sleet"></i>`。

{%note info%}
你也可以使用 CDN 引入：
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/xlovet/asset/css/weather-icons/main.css">
```
{%endnote%}

### 变换

使用下面的类，可以将任何 Weather Icons 图标进行翻转、旋转。

- 水平翻转：`wi-flip-horizontal`
- 垂直翻转：`wi-flip-vertical`
- 旋转 90°：`wi-rotate-90`
- 旋转 180°：`wi-rotate-180`
- 旋转 270°：`wi-rotate-270`
- 固定宽度：`wi fw`

### 图标

下面列出了所有 Weather Icons 图标，点击图标即可将对应的类名复制到你的剪贴板中，例如`wi wi-day-sunny`。

#### 白天

|||||||||||
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
|<i class="wi wi-fw wi-day-sunny" title="day-sunny" data-clipboard-text="wi wi-fw wi-day-sunny"></i>|<i class="wi wi-fw wi-day-cloudy" title="day-cloudy" data-clipboard-text="wi wi-day-cloudy"></i>|<i class="wi wi-fw wi-day-cloudy-gusts" title="day-cloudy-gusts" data-clipboard-text="wi wi-day-cloudy-gusts"></i>|<i class="wi wi-fw wi-day-windy" title="day-windy" data-clipboard-text="wi wi-day-windy"></i>|<i class="wi wi-fw wi-day-fog" title="day-fog" data-clipboard-text="wi wi-day-fog"></i>|<i class="wi wi-fw wi-day-hail" title="day-hail" data-clipboard-text="wi wi-day-hail"></i>|<i class="wi wi-fw wi-day-haze" title="day-haze" data-clipboard-text="wi wi-day-haze"></i>|<i class="wi wi-fw wi-day-lightning" title="day-lightning" data-clipboard-text="wi wi-day-lightning"></i>|<i class="wi wi-fw wi-day-rain" title="day-rain" data-clipboard-text="wi wi-day-rain"></i>|<i class="wi wi-fw wi-day-rain-mix" title="day-rain-mix" data-clipboard-text="wi wi-day-rain-mix"></i>|
|<i class="wi wi-fw wi-day-rain-wind" title="day-rain-wind" data-clipboard-text="wi wi-day-rain-wind"></i>|<i class="wi wi-fw wi-day-showers" title="day-showers" data-clipboard-text="wi wi-day-showers"></i>|<i class="wi wi-fw wi-day-sleet" title="day-sleet" data-clipboard-text="wi wi-day-sleet"></i>|<i class="wi wi-fw wi-day-sleet-storm" title="day-sleet-storm" data-clipboard-text="wi wi-day-sleet-storm"></i>|<i class="wi wi-fw wi-day-snow" title="day-snow" data-clipboard-text="wi wi-day-snow"></i>|<i class="wi wi-fw wi-day-snow-thunderstorm" title="day-snow-thunderstorm" data-clipboard-text="wi wi-day-snow-thunderstorm"></i>|<i class="wi wi-fw wi-day-snow-wind" title="day-snow-wind" data-clipboard-text="wi wi-day-snow-wind"></i>|<i class="wi wi-fw wi-day-sprinkle" title="day-sprinkle" data-clipboard-text="wi wi-day-sprinkle"></i>|<i class="wi wi-fw wi-day-storm-showers" title="day-storm-showers" data-clipboard-text="wi wi-day-storm-showers"></i>|<i class="wi wi-fw wi-day-sunny-overcast" title="day-sunny-overcast" data-clipboard-text="wi wi-day-sunny-overcast"></i>|
|<i class="wi wi-fw wi-day-thunderstorm" title="day-thunderstorm" data-clipboard-text="wi wi-day-thunderstorm"></i>|<i class="wi wi-fw wi-day-windy" title="day-windy" data-clipboard-text="wi wi-day-windy"></i>|<i class="wi wi-fw wi-solar-eclipse" title="solar-eclipse" data-clipboard-text="wi wi-solar-eclipse"></i>|<i class="wi wi-fw wi-hot" title="hot" data-clipboard-text="wi wi-hot"></i>|<i class="wi wi-fw wi-day-cloudy-high" title="day-cloudy-high" data-clipboard-text="wi wi-day-cloudy-high"></i>|<i class="wi wi-fw wi-day-light-wind" title="day-light-wind" data-clipboard-text="wi wi-day-light-wind"></i>|

#### 夜晚

|||||||||||
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
|<i class="wi wi-fw wi-night-clear" title="night-clear" data-clipboard-text="wi wi-night-clear"></i>|<i class="wi wi-fw wi-night-alt-cloudy" title="night-alt-cloudy" data-clipboard-text="wi wi-night-alt-cloudy"></i>|<i class="wi wi-fw wi-night-alt-cloudy-gusts" title="night-alt-cloudy-gusts" data-clipboard-text="wi wi-night-alt-cloudy-gusts"></i>|<i class="wi wi-fw wi-night-alt-cloudy-windy" title="night-alt-cloudy-windy" data-clipboard-text="wi wi-night-alt-cloudy-windy"></i>|<i class="wi wi-fw wi-night-alt-hail" title="night-alt-hail" data-clipboard-text="wi wi-night-alt-hail"></i>|<i class="wi wi-fw wi-night-alt-lightning" title="night-alt-lightning" data-clipboard-text="wi wi-night-alt-lightning"></i>|<i class="wi wi-fw wi-night-alt-rain" title="night-alt-rain" data-clipboard-text="wi wi-night-alt-rain"></i>|<i class="wi wi-fw wi-night-alt-rain-mix" title="night-alt-rain-mix" data-clipboard-text="wi wi-night-alt-rain-mix"></i>|<i class="wi wi-fw wi-night-alt-rain-wind" title="night-alt-rain-wind" data-clipboard-text="wi wi-night-alt-rain-wind"></i>|<i class="wi wi-fw wi-night-alt-showers" title="night-alt-showers" data-clipboard-text="wi wi-night-alt-showers"></i>|
|<i class="wi wi-fw wi-night-alt-sleet" title="night-alt-sleet" data-clipboard-text="wi wi-night-alt-sleet"></i>|<i class="wi wi-fw wi-night-alt-sleet-storm" title="night-alt-sleet-storm" data-clipboard-text="wi wi-night-alt-sleet-storm"></i>|<i class="wi wi-fw wi-night-alt-snow" title="night-alt-snow" data-clipboard-text="wi wi-night-alt-snow"></i>|<i class="wi wi-fw wi-night-alt-snow-thunderstorm" title="night-alt-snow-thunderstorm" data-clipboard-text="wi wi-night-alt-snow-thunderstorm"></i>|<i class="wi wi-fw wi-night-alt-snow-wind" title="night-alt-snow-wind" data-clipboard-text="wi wi-night-alt-snow-wind"></i>|<i class="wi wi-fw wi-night-alt-sprinkle" title="night-alt-sprinkle" data-clipboard-text="wi wi-night-alt-sprinkle"></i>|

#### 中性

|||||||||||
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
|<i class="wi wi-fw wi-cloud" title="cloud" data-clipboard-text="wi wi-cloud"></i>|<i class="wi wi-fw wi-cloudy" title="cloudy" data-clipboard-text="wi wi-cloudy"></i>|<i class="wi wi-fw wi-cloudy-gusts" title="cloudy-gusts" data-clipboard-text="wi wi-cloudy-gusts"></i>|<i class="wi wi-fw wi-cloudy-windy" title="cloudy-windy" data-clipboard-text="wi wi-cloudy-windy"></i>|<i class="wi wi-fw wi-fog" title="fog" data-clipboard-text="wi wi-fog"></i>|<i class="wi wi-fw wi-hail" title="hail" data-clipboard-text="wi wi-hail"></i>|<i class="wi wi-fw wi-rain" title="rain" data-clipboard-text="wi wi-rain"></i>|<i class="wi wi-fw wi-rain-mix" title="rain-mix" data-clipboard-text="wi wi-rain-mix"></i>|<i class="wi wi-fw wi-rain-wind" title="rain-wind" data-clipboard-text="wi wi-rain-wind"></i>|<i class="wi wi-fw wi-showers" title="showers" data-clipboard-text="wi wi-showers"></i>|
|<i class="wi wi-fw wi-sleet" title="sleet" data-clipboard-text="wi wi-sleet"></i>|<i class="wi wi-fw wi-snow" title="snow" data-clipboard-text="wi wi-snow"></i>|<i class="wi wi-fw wi-sprinkle" title="sprinkle" data-clipboard-text="wi wi-sprinkle"></i>|<i class="wi wi-fw wi-cloudy" title="cloudy" data-clipboard-text="wi wi-cloudy"></i>|<i class="wi wi-fw wi-thunderstorm" title="thunderstorm" data-clipboard-text="wi wi-thunderstorm"></i>|<i class="wi wi-fw wi-snow-wind" title="snow-wind" data-clipboard-text="wi wi-snow-wind"></i>|<i class="wi wi-fw wi-smog" title="smog" data-clipboard-text="wi wi-smog"></i>|<i class="wi wi-fw wi-smog" title="smoke" data-clipboard-text="wi wi-smoke"></i>|<i class="wi wi-fw wi-lightning" title="lightning" data-clipboard-text="wi wi-lightning"></i>|<i class="wi wi-fw wi-raindrops" title="raindrops" data-clipboard-text="wi wi-raindrops"></i>|
|<i class="wi wi-fw wi-raindrop" title="raindrop" data-clipboard-text="wi wi-raindrop"></i>|<i class="wi wi-fw wi-dust" title="dust" data-clipboard-text="wi wi-dust"></i>|<i class="wi wi-fw wi-snowflake-cold" title="snowflake-cold" data-clipboard-text="wi wi-snowflake-cold"></i>|<i class="wi wi-fw wi-windy" title="windy" data-clipboard-text="wi wi-windy"></i>|<i class="wi wi-fw wi-strong-wind" title="strong-wind" data-clipboard-text="wi wi-strong-wind"></i>|<i class="wi wi-fw wi-sandstorm" title="sandstorm" data-clipboard-text="wi wi-sandstorm"></i>|<i class="wi wi-fw wi-earthquake" title="earthquake" data-clipboard-text="wi wi-earthquake"></i>|<i class="wi wi-fw wi-fire" title="fire" data-clipboard-text="wi wi-fire"></i>|<i class="wi wi-fw wi-flood" title="flood" data-clipboard-text="wi wi-flood"></i>|<i class="wi wi-fw wi-meteor" title="meteor" data-clipboard-text="wi wi-meteor"></i>|
|<i class="wi wi-fw wi-tsunami" title="tsunami" data-clipboard-text="wi wi-tsunami"></i>|<i class="wi wi-fw wi-volcano" title="volcano" data-clipboard-text="wi wi-volcano"></i>|<i class="wi wi-fw wi-hurricane" title="hurricane" data-clipboard-text="wi wi-hurricane"></i>|<i class="wi wi-fw wi-tornado" title="tornado" data-clipboard-text="wi wi-tornado"></i>|<i class="wi wi-fw wi-small-craft-advisory" title="small-craft-advisory" data-clipboard-text="wi wi-small-craft-advisory"></i>|<i class="wi wi-fw wi-gale-warning" title="gale-warning" data-clipboard-text="wi wi-gale-warning"></i>|<i class="wi wi-fw wi-storm-warning" title="storm-warning" data-clipboard-text="wi wi-storm-warning"></i>|<i class="wi wi-fw wi-hurricane-warning" title="hurricane-warning" data-clipboard-text="wi wi-hurricane-warning"></i>|<i class="wi wi-fw wi-wind-direction" title="wind-direction" data-clipboard-text="wi wi-wind-direction"></i>|

#### 其它

|||||||||||
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
|<i class="wi wi-fw wi-alien" title="alien" data-clipboard-text="wi wi-alien"></i>|<i class="wi wi-fw wi-celsius" title="celsius" data-clipboard-text="wi wi-celsius"></i>|<i class="wi wi-fw wi-fahrenheit" title="fahrenheit" data-clipboard-text="wi wi-fahrenheit"></i>|<i class="wi wi-fw wi-degrees" title="degrees" data-clipboard-text="wi wi-degrees"></i>|<i class="wi wi-fw wi-thermometer" title="thermometer" data-clipboard-text="wi wi-thermometer"></i>|<i class="wi wi-fw wi-thermometer-exterior" title="thermometer-exterior" data-clipboard-text="wi wi-thermometer-exterior"></i>|<i class="wi wi-fw wi-thermometer-internal" title="thermometer-internal" data-clipboard-text="wi wi-thermometer-internal"></i>|<i class="wi wi-fw wi-cloud-down" title="cloud-down" data-clipboard-text="wi wi-cloud-down"></i>|<i class="wi wi-fw wi-cloud-up" title="cloud-up" data-clipboard-text="wi wi-cloud-up"></i>|<i class="wi wi-fw wi-cloud-refresh" title="cloud-refresh" data-clipboard-text="wi wi-cloud-refresh"></i>|
|<i class="wi wi-fw wi-horizon" title="horizon" data-clipboard-text="wi wi-horizon"></i>|<i class="wi wi-fw wi-horizon-alt" title="horizon-alt" data-clipboard-text="wi wi-horizon-alt"></i>|<i class="wi wi-fw wi-sunrise" title="sunrise" data-clipboard-text="wi wi-sunrise"></i>|<i class="wi wi-fw wi-sunset" title="sunset" data-clipboard-text="wi wi-sunset"></i>|<i class="wi wi-fw wi-moonrise" title="moonrise" data-clipboard-text="wi wi-moonrise"></i>|<i class="wi wi-fw wi-moonset" title="moonset" data-clipboard-text="wi wi-moonset"></i>|<i class="wi wi-fw wi-refresh" title="refresh" data-clipboard-text="wi wi-refresh"></i>|<i class="wi wi-fw wi-refresh-alt" title="refresh-alt" data-clipboard-text="wi wi-refresh-alt"></i>|<i class="wi wi-fw wi-umbrella" title="umbrella" data-clipboard-text="wi wi-umbrella"></i>|<i class="wi wi-fw wi-barometer" title="barometer" data-clipboard-text="wi wi-barometer"></i>|
|<i class="wi wi-fw wi-humidity" title="humidity" data-clipboard-text="wi wi-humidity"></i>|<i class="wi wi-fw wi-na" title="na" data-clipboard-text="wi wi-na"></i>|<i class="wi wi-fw wi-train" title="train" data-clipboard-text="wi wi-train"></i>|

#### 月相

|||||||||||
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
|<i class="wi wi-fw wi-moon-new" title="moon-new" data-clipboard-text="wi wi-moon-new"></i>|<i class="wi wi-fw wi-moon-waxing-crescent-1" title="moon-waxing-crescent-1" data-clipboard-text="wi wi-moon-waxing-crescent-1"></i>|<i class="wi wi-fw wi-moon-waxing-crescent-2" title="moon-waxing-crescent-2" data-clipboard-text="wi wi-moon-waxing-crescent-2"></i>|<i class="wi wi-fw wi-moon-waxing-crescent-3" title="moon-waxing-crescent-3" data-clipboard-text="wi wi-moon-waxing-crescent-3"></i>|<i class="wi wi-fw wi-moon-waxing-crescent-4" title="moon-waxing-crescent-4" data-clipboard-text="wi wi-moon-waxing-crescent-4"></i>|<i class="wi wi-fw wi-moon-waxing-crescent-5" title="moon-waxing-crescent-5" data-clipboard-text="wi wi-moon-waxing-crescent-5"></i>|<i class="wi wi-fw wi-moon-waxing-crescent-6" title="moon-waxing-crescent-6" data-clipboard-text="wi wi-moon-waxing-crescent-6"></i>|<i class="wi wi-fw wi-moon-first-quarter" title="moon-first-quarter" data-clipboard-text="wi wi-moon-first-quarter"></i>|<i class="wi wi-fw wi-moon-waxing-gibbous-1" title="moon-waxing-gibbous-1" data-clipboard-text="wi wi-moon-waxing-gibbous-1"></i>|<i class="wi wi-fw wi-moon-waxing-gibbous-2" title="moon-waxing-gibbous-2" data-clipboard-text="wi wi-moon-waxing-gibbous-2"></i>|
|<i class="wi wi-fw wi-moon-waxing-gibbous-3" title="moon-waxing-gibbous-3" data-clipboard-text="wi wi-moon-waxing-gibbous-3"></i>|<i class="wi wi-fw wi-moon-waxing-gibbous-4" title="moon-waxing-gibbous-4" data-clipboard-text="wi wi-moon-waxing-gibbous-4"></i>|<i class="wi wi-fw wi-moon-waxing-gibbous-5" title="moon-waxing-gibbous-5" data-clipboard-text="wi wi-moon-waxing-gibbous-5"></i>|<i class="wi wi-fw wi-moon-waxing-gibbous-6" title="moon-waxing-gibbous-6" data-clipboard-text="wi wi-moon-waxing-gibbous-6"></i>|<i class="wi wi-fw wi-moon-full" title="moon-full" data-clipboard-text="wi wi-moon-full"></i>|<i class="wi wi-fw wi-moon-waning-gibbous-1" title="moon-waning-gibbous-1" data-clipboard-text="wi wi-moon-waning-gibbous-1"></i>|<i class="wi wi-fw wi-moon-waning-gibbous-2" title="moon-waning-gibbous-2" data-clipboard-text="wi wi-moon-waning-gibbous-2"></i>|<i class="wi wi-fw wi-moon-waning-gibbous-3" title="moon-waning-gibbous-3" data-clipboard-text="wi wi-moon-waning-gibbous-3"></i>|<i class="wi wi-fw wi-moon-waning-gibbous-4" title="moon-waning-gibbous-4" data-clipboard-text="wi wi-moon-waning-gibbous-4"></i>|<i class="wi wi-fw wi-moon-waning-gibbous-5" title="moon-waning-gibbous-5" data-clipboard-text="wi wi-moon-waning-gibbous-5"></i>|
|<i class="wi wi-fw wi-moon-waning-gibbous-6" title="moon-waning-gibbous-6" data-clipboard-text="wi wi-moon-waning-gibbous-6"></i>|<i class="wi wi-fw wi-moon-third-quarter" title="moon-third-quarter" data-clipboard-text="wi wi-moon-third-quarter"></i>|<i class="wi wi-fw wi-moon-waning-crescent-1" title="moon-waning-crescent-1" data-clipboard-text="wi wi-moon-waning-crescent-1"></i>|<i class="wi wi-fw wi-moon-waning-crescent-2" title="moon-waning-crescent-2" data-clipboard-text="wi wi-moon-waning-crescent-2"></i>|<i class="wi wi-fw wi-moon-waning-crescent-3" title="moon-waning-crescent-3" data-clipboard-text="wi wi-moon-waning-crescent-3"></i>|<i class="wi wi-fw wi-moon-waning-crescent-4" title="moon-waning-crescent-4" data-clipboard-text="wi wi-moon-waning-crescent-4"></i>|<i class="wi wi-fw wi-moon-waning-crescent-5" title="moon-waning-crescent-5" data-clipboard-text="wi wi-moon-waning-crescent-5"></i>|<i class="wi wi-fw wi-moon-waning-crescent-6" title="moon-waning-crescent-6" data-clipboard-text="wi wi-moon-waning-crescent-6"></i>|<i class="wi wi-fw wi-moon-alt-new" title="moon-alt-new" data-clipboard-text="wi wi-moon-alt-new"></i>|<i class="wi wi-fw wi-moon-alt-waxing-crescent-1" title="moon-alt-waxing-crescent-1" data-clipboard-text="wi wi-moon-alt-waxing-crescent-1"></i>|
|<i class="wi wi-fw wi-moon-alt-waxing-crescent-2" title="moon-alt-waxing-crescent-2" data-clipboard-text="wi wi-moon-alt-waxing-crescent-2"></i>|<i class="wi wi-fw wi-moon-alt-waxing-crescent-3" title="moon-alt-waxing-crescent-3" data-clipboard-text="wi wi-moon-alt-waxing-crescent-3"></i>|<i class="wi wi-fw wi-moon-alt-waxing-crescent-4" title="moon-alt-waxing-crescent-4" data-clipboard-text="wi wi-moon-alt-waxing-crescent-4"></i>|<i class="wi wi-fw wi-moon-alt-waxing-crescent-5" title="moon-alt-waxing-crescent-5" data-clipboard-text="wi wi-moon-alt-waxing-crescent-5"></i>|<i class="wi wi-fw wi-moon-alt-waxing-crescent-6" title="moon-alt-waxing-crescent-6" data-clipboard-text="wi wi-moon-alt-waxing-crescent-6"></i>|<i class="wi wi-fw wi-moon-alt-first-quarter" title="moon-alt-first-quarter" data-clipboard-text="wi wi-moon-alt-first-quarter"></i>|<i class="wi wi-fw wi-moon-alt-waxing-gibbous-1" title="moon-alt-waxing-gibbous-1" data-clipboard-text="wi wi-moon-alt-waxing-gibbous-1"></i>|<i class="wi wi-fw wi-moon-alt-waxing-gibbous-2" title="moon-alt-waxing-gibbous-2" data-clipboard-text="wi wi-moon-alt-waxing-gibbous-2"></i>|<i class="wi wi-fw wi-moon-alt-waxing-gibbous-3" title="moon-alt-waxing-gibbous-3" data-clipboard-text="wi wi-moon-alt-waxing-gibbous-3"></i>|<i class="wi wi-fw wi-moon-alt-waxing-gibbous-4" title="moon-alt-waxing-gibbous-4" data-clipboard-text="wi wi-moon-alt-waxing-gibbous-4"></i>|
|<i class="wi wi-fw wi-moon-alt-waxing-gibbous-5" title="moon-alt-waxing-gibbous-5" data-clipboard-text="wi wi-moon-alt-waxing-gibbous-5"></i>|<i class="wi wi-fw wi-moon-alt-waxing-gibbous-6" title="moon-alt-waxing-gibbous-6" data-clipboard-text="wi wi-moon-alt-waxing-gibbous-6"></i>|<i class="wi wi-fw wi-moon-alt-full" title="moon-alt-full" data-clipboard-text="wi wi-moon-alt-full"></i>|<i class="wi wi-fw wi-moon-alt-waning-gibbous-1" title="moon-alt-waning-gibbous-1" data-clipboard-text="wi wi-moon-alt-waning-gibbous-1"></i>|<i class="wi wi-fw wi-moon-alt-waning-gibbous-2" title="moon-alt-waning-gibbous-2" data-clipboard-text="wi wi-moon-alt-waning-gibbous-2"></i>|<i class="wi wi-fw wi-moon-alt-waning-gibbous-3" title="moon-alt-waning-gibbous-3" data-clipboard-text="wi wi-moon-alt-waning-gibbous-3"></i>|<i class="wi wi-fw wi-moon-alt-waning-gibbous-4" title="moon-alt-waning-gibbous-4" data-clipboard-text="wi wi-moon-alt-waning-gibbous-4"></i>|<i class="wi wi-fw wi-moon-alt-waning-gibbous-5" title="moon-alt-waning-gibbous-5" data-clipboard-text="wi wi-moon-alt-waning-gibbous-5"></i>|<i class="wi wi-fw wi-moon-alt-waning-gibbous-6" title="moon-alt-waning-gibbous-6" data-clipboard-text="wi wi-moon-alt-waning-gibbous-6"></i>|<i class="wi wi-fw wi-moon-alt-third-quarter" title="moon-alt-third-quarter" data-clipboard-text="wi wi-moon-alt-third-quarter"></i>|
|<i class="wi wi-fw wi-moon-alt-waning-crescent-1" title="moon-alt-waning-crescent-1" data-clipboard-text="wi wi-moon-alt-waning-crescent-1"></i>|<i class="wi wi-fw wi-moon-alt-waning-crescent-2" title="moon-alt-waning-crescent-2" data-clipboard-text="wi wi-moon-alt-waning-crescent-2"></i>|<i class="wi wi-fw wi-moon-alt-waning-crescent-3" title="moon-alt-waning-crescent-3" data-clipboard-text="wi wi-moon-alt-waning-crescent-3"></i>|<i class="wi wi-fw wi-moon-alt-waning-crescent-4" title="moon-alt-waning-crescent-4" data-clipboard-text="wi wi-moon-alt-waning-crescent-4"></i>|<i class="wi wi-fw wi-moon-alt-waning-crescent-5" title="moon-alt-waning-crescent-5" data-clipboard-text="wi wi-moon-alt-waning-crescent-5"></i>|<i class="wi wi-fw wi-moon-alt-waning-crescent-6" title="moon-alt-waning-crescent-6" data-clipboard-text="wi wi-moon-alt-waning-crescent-6"></i>|

#### 时间

|||||||||||
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
|<i class="wi wi-fw wi-time-1" title="time-1" data-clipboard-text="wi wi-time-1"></i>|<i class="wi wi-fw wi-time-2" title="time-2" data-clipboard-text="wi wi-time-2"></i>|<i class="wi wi-fw wi-time-3" title="time-3" data-clipboard-text="wi wi-time-3"></i>|<i class="wi wi-fw wi-time-4" title="time-4" data-clipboard-text="wi wi-time-4"></i>|<i class="wi wi-fw wi-time-5" title="time-5" data-clipboard-text="wi wi-time-5"></i>|<i class="wi wi-fw wi-time-6" title="time-6" data-clipboard-text="wi wi-time-6"></i>|<i class="wi wi-fw wi-time-7" title="time-7" data-clipboard-text="wi wi-time-7"></i>|<i class="wi wi-fw wi-time-8" title="time-8" data-clipboard-text="wi wi-time-8"></i>|<i class="wi wi-fw wi-time-9" title="time-9" data-clipboard-text="wi wi-time-9"></i>|<i class="wi wi-fw wi-time-10" title="time-10" data-clipboard-text="wi wi-time-10"></i>|
|<i class="wi wi-fw wi-time-11" title="time-11" data-clipboard-text="wi wi-time-11"></i>|<i class="wi wi-fw wi-time-12" title="time-12" data-clipboard-text="wi wi-time-12"></i>|

#### 箭头

|||||||||
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
|<i class="wi wi-fw wi-direction-up" title="direction-up" data-clipboard-text="wi wi-direction-up"></i>|<i class="wi wi-fw wi-direction-up-right" title="direction-up-right" data-clipboard-text="wi wi-direction-up-right"></i>|<i class="wi wi-fw wi-direction-right" title="direction-right" data-clipboard-text="wi wi-direction-right"></i>|<i class="wi wi-fw wi-direction-down-right" title="direction-down-right" data-clipboard-text="wi wi-direction-down-right"></i>|<i class="wi wi-fw wi-direction-down" title="direction-down" data-clipboard-text="wi wi-direction-down"></i>|<i class="wi wi-fw wi-direction-down-left" title="direction-down-left" data-clipboard-text="wi wi-direction-down-left"></i>|<i class="wi wi-fw wi-direction-left" title="direction-left" data-clipboard-text="wi wi-direction-left"></i>|<i class="wi wi-fw wi-direction-up-left" title="direction-up-left" data-clipboard-text="wi wi-direction-up-left"></i>|

#### 风度

{%note danger%}
要显示风度图标，你需要添加 3 个类，即基础图标类，风向图标类，然后添加你要面对的方向：

`class="wi wi-wind torwrds-23-deg"`

你必须包含 [weather-iconds-wind.css](https://cdn.jsdelivr.net/gh/xlovet/asset/css/weather-icons/wind.css) 样式表才能使用风度图标。
{%endnote%}

|||||||||||
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
|<i class="wi wi-fw wi-wind towards-0-deg" title="towards-0-deg" data-clipboard-text="wi wi-wind towards-0-deg"></i>|<i class="wi wi-fw wi-wind towards-23-deg" title="towards-23-deg" data-clipboard-text="wi wi-wind towards-23-deg"></i>|<i class="wi wi-fw wi-wind towards-45-deg" title="towards-45-deg" data-clipboard-text="wi wi-wind towards-45-deg"></i>|<i class="wi wi-fw wi-wind towards-68-deg" title="towards-68-deg" data-clipboard-text="wi wi-wind towards-68-deg"></i>|<i class="wi wi-fw wi-wind towards-90-deg" title="towards-90-deg" data-clipboard-text="wi wi-wind towards-90-deg"></i>|<i class="wi wi-fw wi-wind towards-113-deg" title="towards-113-deg" data-clipboard-text="wi wi-wind towards-113-deg"></i>|<i class="wi wi-fw wi-wind towards-135-deg" title="towards-135-deg" data-clipboard-text="wi wi-wind towards-135-deg"></i>|<i class="wi wi-fw wi-wind towards-158-deg" title="towards-158-deg" data-clipboard-text="wi wi-wind towards-158-deg"></i>|<i class="wi wi-fw wi-wind towards-180-deg" title="towards-180-deg" data-clipboard-text="wi wi-wind towards-180-deg"></i>|<i class="wi wi-fw wi-wind towards-203-deg" title="towards-203-deg" data-clipboard-text="wi wi-wind towards-203-deg"></i>|
|<i class="wi wi-fw wi-wind towards-225-deg" title="towards-225-deg" data-clipboard-text="wi wi-wind towards-225-deg"></i>|<i class="wi wi-fw wi-wind towards-248-deg" title="towards-248-deg" data-clipboard-text="wi wi-wind towards-248-deg"></i>|<i class="wi wi-fw wi-wind towards-270-deg" title="towards-270-deg" data-clipboard-text="wi wi-wind towards-270-deg"></i>|<i class="wi wi-fw wi-wind towards-293-deg" title="towards-293-deg" data-clipboard-text="wi wi-wind towards-293-deg"></i>|<i class="wi wi-fw wi-wind towards-313-deg" title="towards-313-deg" data-clipboard-text="wi wi-wind towards-313-deg"></i>|<i class="wi wi-fw wi-wind towards-336-deg" title="towards-336-deg" data-clipboard-text="wi wi-wind towards-336-deg"></i>|<i class="wi wi-fw wi-wind from-180-deg" title="from-180-deg" data-clipboard-text="wi wi-wind from-180-deg"></i>|<i class="wi wi-fw wi-wind from-203-deg" title="from-203-deg" data-clipboard-text="wi wi-wind from-203-deg"></i>|<i class="wi wi-fw wi-wind from-225-deg" title="from-225-deg" data-clipboard-text="wi wi-wind from-225-deg"></i>|<i class="wi wi-fw wi-wind from-248-deg" title="from-248-deg" data-clipboard-text="wi wi-wind from-248-deg"></i>|
|<i class="wi wi-fw wi-wind from-270-deg" title="from-270-deg" data-clipboard-text="wi wi-wind from-270-deg"></i>|<i class="wi wi-fw wi-wind from-293-deg" title="from-293-deg" data-clipboard-text="wi wi-wind from-293-deg"></i>|<i class="wi wi-fw wi-wind from-313-deg" title="from-313-deg" data-clipboard-text="wi wi-wind from-313-deg"></i>|<i class="wi wi-fw wi-wind from-336-deg" title="from-336-deg" data-clipboard-text="wi wi-wind from-336-deg"></i>|<i class="wi wi-fw wi-wind from-0-deg" title="from-0-deg" data-clipboard-text="wi wi-wind from-0-deg"></i>|<i class="wi wi-fw wi-wind from-23-deg" title="from-23-deg" data-clipboard-text="wi wi-wind from-23-deg"></i>|<i class="wi wi-fw wi-wind from-45-deg" title="from-45-deg" data-clipboard-text="wi wi-wind from-45-deg"></i>|<i class="wi wi-fw wi-wind from-68-deg" title="from-68-deg" data-clipboard-text="wi wi-wind from-68-deg"></i>|<i class="wi wi-fw wi-wind from-90-deg" title="from-90-deg" data-clipboard-text="wi wi-wind from-90-deg"></i>|<i class="wi wi-fw wi-wind from-113-deg" title="from-113-deg" data-clipboard-text="wi wi-wind from-113-deg"></i>|
|<i class="wi wi-fw wi-wind from-135-deg" title="from-135-deg" data-clipboard-text="wi wi-wind from-135-deg"></i>|<i class="wi wi-fw wi-wind from-158-deg" title="from-158-deg" data-clipboard-text="wi wi-wind from-158-deg"></i>|


#### 风向

{%note danger%}
要显示风向图标，你需要添加 3 个类，即基础图标类，风向图标类，然后添加你要面对的方向：

`class="wi wi-wind wi-from-e"`

你必须包含 [weather-iconds-wind.css](https://cdn.jsdelivr.net/gh/xlovet/asset/css/weather-icons/wind.css) 样式表才能使用风向图标。
{%endnote%}

|||||||||||
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
|<i class="wi wi-fw wi-wind wi-towards-n" title="towards-n" data-clipboard-text="wi wi-wind wi-towards-n"></i>|<i class="wi wi-fw wi-wind wi-towards-nne" title="towards-nne" data-clipboard-text="wi wi-wind wi-towards-nne"></i>|<i class="wi wi-fw wi-wind wi-towards-ne" title="towards-ne" data-clipboard-text="wi wi-wind wi-towards-ne"></i>|<i class="wi wi-fw wi-wind wi-towards-ene" title="towards-ene" data-clipboard-text="wi wi-wind wi-towards-ene"></i>|<i class="wi wi-fw wi-wind wi-towards-e" title="wi-towards-e" data-clipboard-text="wi wi-wind wi-towards-e"></i>|<i class="wi wi-fw wi-wind wi-towards-ese" title="towards-ese" data-clipboard-text="wi wi-wind wi-towards-ese"></i>|<i class="wi wi-fw wi-wind wi-towards-se" title="towards-se" data-clipboard-text="wi wi-wind wi-towards-se"></i>|<i class="wi wi-fw wi-wind wi-towards-sse" title="towards-sse" data-clipboard-text="wi wi-wind wi-towards-sse"></i>|<i class="wi wi-fw wi-wind wi-towards-s" title="towards-s" data-clipboard-text="wi wi-wind wi-towards-s"></i>|<i class="wi wi-fw wi-wind wi-towards-ssw" title="towards-ssw" data-clipboard-text="wi wi-wind wi-towards-ssw"></i>|
|<i class="wi wi-fw wi-wind wi-towards-sw" title="towards-sw" data-clipboard-text="wi wi-wind wi-towards-sw"></i>|<i class="wi wi-fw wi-wind wi-towards-wsw" title="towards-wsw" data-clipboard-text="wi wi-wind wi-towards-wsw"></i>|<i class="wi wi-fw wi-wind wi-towards-w" title="towards-w" data-clipboard-text="wi wi-wind wi-towards-w"></i>|<i class="wi wi-fw wi-wind wi-towards-wnw" title="towards-wnw" data-clipboard-text="wi wi-wind wi-towards-wnw"></i>|<i class="wi wi-fw wi-wind wi-towards-nw" title="towards-nw" data-clipboard-text="wi wi-wind wi-towards-nw"></i>|<i class="wi wi-fw wi-wind wi-towards-nnw" title="towards-nnw" data-clipboard-text="wi wi-wind wi-towards-nnw"></i>|<i class="wi wi-fw wi-wind wi-from-n" title="from-n" data-clipboard-text="wi wi-wind wi-from-n"></i>|<i class="wi wi-fw wi-wind wi-from-nne" title="from-nne" data-clipboard-text="wi wi-wind wi-from-nne"></i>|<i class="wi wi-fw wi-wind wi-from-ne" title="from-ne" data-clipboard-text="wi wi-wind wi-from-ne"></i>|<i class="wi wi-fw wi-wind wi-from-ene" title="from-ene" data-clipboard-text="wi wi-wind wi-from-ene"></i>|
|<i class="wi wi-fw wi-wind wi-from-e" title="from-e" data-clipboard-text="wi wi-wind wi-from-e"></i>|<i class="wi wi-fw wi-wind wi-from-ese" title="from-ese" data-clipboard-text="wi wi-wind wi-from-ese"></i>|<i class="wi wi-fw wi-wind wi-from-se" title="from-se" data-clipboard-text="wi wi-wind wi-from-se"></i>|<i class="wi wi-fw wi-wind wi-from-sse" title="from-sse" data-clipboard-text="wi wi-wind wi-from-sse"></i>|<i class="wi wi-fw wi-wind wi-from-s" title="from-s" data-clipboard-text="wi wi-wind wi-from-s"></i>|<i class="wi wi-fw wi-wind wi-from-ssw" title="from-ssw" data-clipboard-text="wi wi-wind wi-from-ssw"></i>|<i class="wi wi-fw wi-wind wi-from-sw" title="from-sw" data-clipboard-text="wi wi-wind wi-from-sw"></i>|<i class="wi wi-fw wi-wind wi-from-wsw" title="from-wsw" data-clipboard-text="wi wi-wind wi-from-wsw"></i>|<i class="wi wi-fw wi-wind wi-from-w" title="from-w" data-clipboard-text="wi wi-wind wi-from-w"></i>|<i class="wi wi-fw wi-wind wi-from-wnw" title="from-wnw" data-clipboard-text="wi wi-wind wi-from-wnw"></i>|
|<i class="wi wi-fw wi-wind wi-from-nw" title="from-nw" data-clipboard-text="wi wi-wind wi-from-nw"></i>|<i class="wi wi-fw wi-wind wi-from-nnw" title="from-nnw" data-clipboard-text="wi wi-wind wi-from-nnw"></i>|

#### 蒲氏风级

|||||||||||
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
|<i class="wi wi-fw wi-wind-beaufort-0" title="wind-beaufort-0" data-clipboard-text="wi wi-wind-beaufort-0"></i>|<i class="wi wi-fw wi-wind-beaufort-1" title="wind-beaufort-1" data-clipboard-text="wi wi-wind-beaufort-1"></i>|<i class="wi wi-fw wi-wind-beaufort-2" title="wind-beaufort-2" data-clipboard-text="wi wi-wind-beaufort-2"></i>|<i class="wi wi-fw wi-wind-beaufort-3" title="wind-beaufort-3" data-clipboard-text="wi wi-wind-beaufort-3"></i>|<i class="wi wi-fw wi-wind-beaufort-4" title="wind-beaufort-4" data-clipboard-text="wi wi-wind-beaufort-4"></i>|<i class="wi wi-fw wi-wind-beaufort-5" title="wind-beaufort-5" data-clipboard-text="wi wi-wind-beaufort-5"></i>|<i class="wi wi-fw wi-wind-beaufort-6" title="wind-beaufort-6" data-clipboard-text="wi wi-wind-beaufort-6"></i>|<i class="wi wi-fw wi-wind-beaufort-7" title="wind-beaufort-7" data-clipboard-text="wi wi-wind-beaufort-7"></i>|<i class="wi wi-fw wi-wind-beaufort-8" title="wind-beaufort-8" data-clipboard-text="wi wi-wind-beaufort-8"></i>|<i class="wi wi-fw wi-wind-beaufort-9" title="wind-beaufort-9" data-clipboard-text="wi wi-wind-beaufort-9"></i>|
|<i class="wi wi-fw wi-wind-beaufort-10" title="wind-beaufort-10" data-clipboard-text="wi wi-wind-beaufort-10"></i>|<i class="wi wi-fw wi-wind-beaufort-11" title="wind-beaufort-11" data-clipboard-text="wi wi-wind-beaufort-11"></i>|<i class="wi wi-fw wi-wind-beaufort-12" title="wind-beaufort-12" data-clipboard-text="wi wi-wind-beaufort-12"></i>|
