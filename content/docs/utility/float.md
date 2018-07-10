+++
title = "Float"
date = "2018-04-11T09:16:45+12:00"
draft = false
description = "The float component forces float of any given element."
+++

##### Basic Usage

Defined with `u-float` and direction.

<div class="row margin-bottom:2">
  <div class="item -span-6">
    <div class="s-thumb u-float-left">
      <img src="https://placeimg.com/500/500/people">
    </div>
  </div>
</div>
<div class="row margin-bottom:2">
  <div class="item -span-6">
    <div class="s-thumb u-float-right">
      <img src="https://placeimg.com/500/500/people">
    </div>
  </div>
</div>
<div class="row margin-bottom:2">
  <div class="item -span-6">
    <div class="s-thumb u-float-none">
      <img src="https://placeimg.com/500/500/people">
    </div>
  </div>
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="u-float-left">
  ...
</div>
<div class="u-float-right">
  ...
</div>
<div class="u-float-none">
  ...
</div>
```
{{% /codeblock %}}

##### Responsive Floats

You can assign responsive floats by adding device specific extensions.

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="u-float-left-sm">
  ...
</div>
<div class="u-float-right-md">
  ...
</div>
<div class="u-float-none-lg">
  ...
</div>
```
{{% /codeblock %}}
