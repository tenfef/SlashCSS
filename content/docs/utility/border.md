+++
title = "Border"
date = "2018-04-11T09:16:45+12:00"
draft = false
description = "The Border component applies borders to block elements."
+++

##### Basic Usage

Defined with `u-border`. Default border color settings are applied.

<div class="u-border u-pad-5 u-fill-shade-1 margin-bottom:2">
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="u-border">

</div>
```
{{% /codeblock %}}

##### Directional Borders

You can apply borders on one side only by adding direction.

<div class="u-border-top u-pad-5 u-fill-shade-1 margin-bottom:2">
</div>

<div class="u-border-right u-pad-5 u-fill-shade-1 margin-bottom:2">
</div>

<div class="u-border-bottom u-pad-5 u-fill-shade-1 margin-bottom:2">
</div>

<div class="u-border-left u-pad-5 u-fill-shade-1 margin-bottom:2">
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="u-border-top">
</div>

<div class="u-border-right">
</div>

<div class="u-border-bottom">
</div>

<div class="u-border-left">
</div>
```
{{% /codeblock %}}

##### Other Border Properties

Border radius, or removal of borders can also be applied.

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="u-border-radius">
</div>

<div class="u-border-none">
</div>
```
{{% /codeblock %}}
