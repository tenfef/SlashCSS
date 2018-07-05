+++
title = "distribute"
date = "2018-04-11T09:16:45+12:00"
draft = false
description = "The distribute component takes advantage of the Sam Pickering's Labotomized Owl to vertically or horizontally distribute child elements."
+++

##### Basic Usage

Defined with `u-spread` and specifying direction. You can distribute child elements horiontally or vertically with `x` and `y` extensions. Standard gap ranges apply.

<div class="u-spread-x-2 margin-bottom:2">
	<div class="s-thumb u-fill-shade-2 u-border-radius"></div>
	<div class="s-thumb u-fill-shade-2 u-border-radius"></div>
	<div class="s-thumb u-fill-shade-2 u-border-radius"></div>
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="u-spread-x-2">
	...
</div>
```
{{% /codeblock %}}

##### Responsive Spreads

To apply responsive spreads add standard device specific extensions.

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="u-spread-x-md-2">
	...
</div>
<div class="u-spread-x-lg-2">
	...
</div>
```
{{% /codeblock %}}
