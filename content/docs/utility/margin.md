+++
title = "Margin"
date = "2018-04-11T09:16:45+12:00"
draft = false
description = "The margin component adds margin to any object or container."
+++

##### Basic Usage

Defind with `u-margin`. There are 10 basic levels of margin based on standard grid rhythm that can be applied. Additionally, you can also add `-auto` to allow for auto margin layout or `-none` to remove margin.

<div class="margin:auto">
  <div class="padding:2 fill:red">
  </div>
</div>
<div class="margin:0">
  <div class="padding:2 fill:red">
  </div>
</div>
<div class="margin:1">
  <div class="padding:2 fill:red">
  </div>
</div>
<div class="margin:2">
  <div class="padding:2 fill:red">
  </div>
</div>
<div class="margin:3">
  <div class="padding:2 fill:red">
  </div>
</div>
<div class="margin:4">
  <div class="padding:2 fill:red">
  </div>
</div>
<div class="margin:5">
  <div class="padding:2 fill:red">
  </div>
</div>
<div class="margin:6">
  <div class="padding:2 fill:red">
  </div>
</div>
<div class="margin:7">
  <div class="padding:2 fill:red">
  </div>
</div>
<div class="margin:8">
  <div class="padding:2 fill:red">
  </div>
</div>
<div class="margin:9">
  <div class="padding:2 fill:red">
  </div>
</div>
<div class="margin:10">
  <div class="padding:2 fill:red">
  </div>
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="margin:auto">
  ...
</div>
<div class="margin:0">
  ...
</div>
<div class="margin:1">
  ...
</div>
<div class="margin:2">
  ...
</div>
<div class="margin:3">
  ...
</div>
<div class="margin:4">
  ...
</div>
<div class="margin:5">
  ...
</div>
<div class="margin:6">
  ...
</div>
<div class="margin:7">
  ...
</div>
<div class="margin:8">
  ...
</div>
<div class="margin:9">
  ...
</div>
<div class="margin:10">
  ...
</div>
```
{{% /codeblock %}}

##### Directional Margins

Margin can be applied to `top` `right` `bottom` `left`. It can also be applied to only the horizontal and vertical axis.

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="margin-top-1">
  ...
</div>
<div class="margin-right-2">
  ...
</div>
<div class="margin-bottom:3">
  ...
</div>
<div class="margin-left-4">
  ...
</div>
<div class="margin:x-5">
  ...
</div>
<div class="margin:y-6">
  ...
</div>
```
{{% /codeblock %}}

##### Responsive Margins

To apply responsive margins add device specific extensions

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="margin-top-sm-1">
  ...
</div>
<div class="margin-right-md-5">
  ...
</div>
```
{{% /codeblock %}}

##### Viewport Margins

The margin component also supports viewport based margins that range from 1 to 20 vh/vw respectively.

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="margin-top-10vh">
  ...
</div>
<div class="margin-right-md-5vh">
  ...
</div>
```
{{% /codeblock %}}
