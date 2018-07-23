+++
title = "Distribute"
date = "2018-04-11T09:16:45+12:00"
draft = false
description = "The distribute component takes advantage of the Sam Pickering's Labotomized Owl to vertically or horizontally distribute child elements."
+++

### Basic Usage

Defined with `distribute`. You can distribute child elements horiontally or vertically with `x` and `y` suffix. You can also apply responsive suffixes.

<div class="distribute-x:5 margin-bottom:2">
	<div class="display:inline-block media-size:3 fill:grey-l3"></div>
	<div class="display:inline-block media-size:3 fill:grey-l3"></div>
	<div class="display:inline-block media-size:3 fill:grey-l3"></div>
</div>
<div class="distribute-y:1 margin-bottom:2 margin-right:2">
	<div class="media-size:3 fill:grey-l3"></div>
	<div class="media-size:3 fill:grey-l3"></div>
	<div class="media-size:3 fill:grey-l3"></div>
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="distribute-x:5">
	...
</div>
<div class="distribute-y:1">
	...
</div>
```
{{% /codeblock %}}

### Local Variables

You can override styling using the following local variables.

{{% codeblock key="language" definition="css" margin="bottom" %}}
```css
$distribute-gutters: 5 !default;
```
{{% /codeblock %}}

### Options

The following modifiers are available.

<table class="table width:100% table:pile table@sm:unpile">
  <thead>
    <tr>
      <th>
        Property
      </th>
      <th>
        Modifier
      </th>
      <th>
        Responsive
      </th>
      <th>
        Description
      </th>
    </tr>
  </thead>
  <tr>
    <td data-label="Properties">
      <code>distribute-[axis]</code>
    </td>
    <td data-label="Attributes">
      <code>:1</code> ... <code>:5</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td class="row:reverse">
      Distribute child elements horizontally or vertically
    </td>
  </tr>
</table>
