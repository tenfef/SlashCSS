+++
title = "Distribute"
date = "2018-04-11T09:16:45+12:00"
family = "Utility"
draft = false
description = "The distribute component takes advantage of the Sam Pickering's Labotomized Owl to vertically or horizontally distribute child elements."
+++

### Basic Usage

Defined with `distribute`. You can distribute child elements horiontally or vertically with `x` and `y` suffix. You can also apply responsive suffixes.

<div class="distribute-x:u6 margin-bottom:u2">
	<div class="display:inline-block media-size:md fill:grey-l3"></div>
	<div class="display:inline-block media-size:md fill:grey-l3"></div>
	<div class="display:inline-block media-size:md fill:grey-l3"></div>
</div>
<div class="distribute-y:u2 margin-bottom:u2 margin-right:u4">
	<div class="media-size:md fill:grey-l3"></div>
	<div class="media-size:md fill:grey-l3"></div>
	<div class="media-size:md fill:grey-l3"></div>
</div>

```html
<div class="distribute-x:u6">
	...
</div>
<div class="distribute-y:u2">
	...
</div>
```

### Local Variables

You can override this component using the following local variables.

```css
$distribute-gutters: 5 !default;
```

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
      <code>:u2</code> <code>:u4</code> <code>:u6</code> <code>:u8</code> <code>:u10</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td class="row:reverse">
      Distribute child elements horizontally or vertically
    </td>
  </tr>
</table>
