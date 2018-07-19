+++
title = "Padding"
date = "2018-04-11T09:16:45+12:00"
draft = false
description = "The padding component adds padding to any object or container."
+++

##### Basic Usage

Defind with `u-padding`. There are 11 basic levels of padding based on standard grid rhythm that can be applied. Additionally, you can also add `-none` to remove padding.

<div class="padding-top:0 fill:blue">
</div>
<div class="padding-top:1 fill:blue-l3">
</div>
<div class="padding-top:2 fill:blue">
</div>
<div class="padding-top:3 fill:blue-l3">
</div>
<div class="padding-top:4 fill:blue">
</div>
<div class="padding-top:5 fill:blue-l3">
</div>
<div class="padding-top:6 fill:blue">
</div>
<div class="padding-top:7 fill:blue-l3">
</div>
<div class="padding-top:8 fill:blue">
</div>
<div class="padding-top:9 fill:blue-l3">
</div>
<div class="padding-top:10 fill:blue">
</div>
<div class="padding-top:11 fill:blue-l3">
</div>
<div class="padding-top:12 fill:blue">
</div>
<div class="padding-top:13 fill:blue-l3">
</div>
<div class="padding-top:14 fill:blue">
</div>
<div class="padding-top:15 fill:blue-l3">
</div>
<div class="padding-top:16 fill:blue">
</div>
<div class="padding-top:17 fill:blue-l3">
</div>
<div class="padding-top:18 fill:blue">
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="padding:0">
  ...
</div>
<div class="padding:1">
  ...
</div>
<div class="padding:2">
  ...
</div>
<div class="padding:3">
  ...
</div>
<div class="padding:4">
  ...
</div>
<div class="padding:5">
  ...
</div>
<div class="padding:6">
  ...
</div>
<div class="padding:7">
  ...
</div>
<div class="padding:8">
  ...
</div>
<div class="padding:9">
  ...
</div>
<div class="padding:10">
  ...
</div>
```
{{% /codeblock %}}

##### Directional Padding

Margin can be applied to `top` `right` `bottom` `left`. It can also be applied to only the horizontal and vertical axis.

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="padding-top-1">
  ...
</div>
<div class="padding-right-2">
  ...
</div>
<div class="padding-bottom-3">
  ...
</div>
<div class="padding-left-4">
  ...
</div>
<div class="padding-x-5">
  ...
</div>
<div class="padding-y-6">
  ...
</div>
```
{{% /codeblock %}}

##### Responsive Padding

To apply responsive paddings add device specific extensions

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="padding-top-sm-1">
  ...
</div>
<div class="padding-right-md-5">
  ...
</div>
```
{{% /codeblock %}}

##### Viewport Padding

The padding component also supports viewport based paddings that range from 1 to 20 vh/vw respectively.

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="padding-top-10vh">
  ...
</div>
<div class="padding-right-md-5vh">
  ...
</div>
```
{{% /codeblock %}}
