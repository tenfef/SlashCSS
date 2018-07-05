+++
title = "Margin"
date = "2018-04-11T09:16:45+12:00"
draft = false
description = "The margin component adds margin to any object or container."
+++

##### Basic Usage

Defind with `u-margin`. There are 10 basic levels of margin based on standard grid rhythm that can be applied. Additionally, you can also add `-auto` to allow for auto margin layout or `-none` to remove margin.

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="u-margin-auto">
  ...
</div>
<div class="u-margin-0">
  ...
</div>
<div class="u-margin-1">
  ...
</div>
<div class="u-margin-2">
  ...
</div>
<div class="u-margin-3">
  ...
</div>
<div class="u-margin-4">
  ...
</div>
<div class="u-margin-5">
  ...
</div>
<div class="u-margin-6">
  ...
</div>
<div class="u-margin-7">
  ...
</div>
<div class="u-margin-8">
  ...
</div>
<div class="u-margin-9">
  ...
</div>
<div class="u-margin-10">
  ...
</div>
```
{{% /codeblock %}}

##### Directional Margins

Margin can be applied to `top` `right` `bottom` `left`. It can also be applied to only the horizontal and vertical axis.

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="u-margin-top-1">
  ...
</div>
<div class="u-margin-right-2">
  ...
</div>
<div class="margin-bottom:3">
  ...
</div>
<div class="u-margin-left-4">
  ...
</div>
<div class="u-margin-x-5">
  ...
</div>
<div class="u-margin-y-6">
  ...
</div>
```
{{% /codeblock %}}

##### Responsive Margins

To apply responsive margins add device specific extensions

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="u-margin-top-sm-1">
  ...
</div>
<div class="u-margin-right-md-5">
  ...
</div>
```
{{% /codeblock %}}

##### Viewport Margins

The margin component also supports viewport based margins that range from 1 to 20 vh/vw respectively.

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="u-margin-top-10vh">
  ...
</div>
<div class="u-margin-right-md-5vh">
  ...
</div>
```
{{% /codeblock %}}
