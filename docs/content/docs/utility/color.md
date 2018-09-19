+++
title = "Color"
date = "2018-04-11T09:16:45+12:00"
family = "Utility"
draft = false
description = "The color components applies colors to text elements."
+++

### Basic Colors

Defined with `color`, the following base colors are available.

<h6 class="font-height:0 font-weight:medium margin:u0 margin-bottom:u2 color:red">Red</h6>
<h6 class="font-height:0 font-weight:medium margin:u0 margin-bottom:u2 color:pink">Pink</h6>
<h6 class="font-height:0 font-weight:medium margin:u0 margin-bottom:u2 color:violet">Violet</h6>
<h6 class="font-height:0 font-weight:medium margin:u0 margin-bottom:u2 color:purple">Purple</h6>
<h6 class="font-height:0 font-weight:medium margin:u0 margin-bottom:u2 color:navy">Bavy</h6>
<h6 class="font-height:0 font-weight:medium margin:u0 margin-bottom:u2 color:blue">Blue</h6>
<h6 class="font-height:0 font-weight:medium margin:u0 margin-bottom:u2 color:teal">Teal</h6>
<h6 class="font-height:0 font-weight:medium margin:u0 margin-bottom:u2 color:green">Green</h6>
<h6 class="font-height:0 font-weight:medium margin:u0 margin-bottom:u2 color:lime">Lime</h6>
<h6 class="font-height:0 font-weight:medium margin:u0 margin-bottom:u2 color:yellow">Yellow</h6>
<h6 class="font-height:0 font-weight:medium margin:u0 margin-bottom:u2 color:orange">Orange</h6>
<h6 class="font-height:0 font-weight:medium margin:u0 margin-bottom:u2 color:brown">Brown</h6>
<h6 class="font-height:0 font-weight:medium margin:u0 margin-bottom:u2 color:grey">Grey</h6>
<h6 class="font-height:0 font-weight:medium margin:u0 margin-bottom:u2 color:white fill:black display:inline-block">White</h6>
<h6 class="font-height:0 font-weight:medium margin:u0 margin-bottom:u2 color:black">Black</h6>
<h6 class="font-height:0 font-weight:medium margin:u0 margin-bottom:u2 color:primary">Primary</h6>
<h6 class="font-height:0 font-weight:medium margin:u0 margin-bottom:u2 color:secondary">Secondary</h6>
<h6 class="font-height:0 font-weight:medium margin:u0 margin-bottom:u4 color:tertiary">Tertiary</h6>



```html
<h6 class="color:red">Red</h6>
<h6 class="color:pink">Pink</h6>
<h6 class="color:violet">Violet</h6>
<h6 class="color:purple">Purple</h6>
<h6 class="color:navy">Bavy</h6>
<h6 class="color:blue">Blue</h6>
<h6 class="color:teal">Teal</h6>
<h6 class="color:green">Green</h6>
<h6 class="color:lime">Lime</h6>
<h6 class="color:yellow">Yellow</h6>
<h6 class="color:orange">Orange</h6>
<h6 class="color:brown">Brown</h6>
<h6 class="color:grey">Grey</h6>
<h6 class="color:white">White</h6>
<h6 class="color:black">Black</h6>
<h6 class="color:primary">Primary</h6>
<h6 class="color:secondary">Secondary</h6>
<h6 class="color:tertiary">Tertiary</h6>
```

### Tonal Colors

Each base color has 5 light and 5 dark tones available. These can be applied with the color modifier plus `-l` or `-d` suffix. Tonal variants are not available for white and black.

<h6 class="font-height:0 font-weight:medium margin:u0 margin-bottom:u2 color:red-l5">Red Light 5</h6>
<h6 class="font-height:0 font-weight:medium margin:u0 margin-bottom:u2 color:red-l4">Red Light 4</h6>
<h6 class="font-height:0 font-weight:medium margin:u0 margin-bottom:u2 color:red-l3">Red Light 3</h6>
<h6 class="font-height:0 font-weight:medium margin:u0 margin-bottom:u2 color:red-l2">Red Light 2</h6>
<h6 class="font-height:0 font-weight:medium margin:u0 margin-bottom:u2 color:red-l1">Red Light 1</h6>
<h6 class="font-height:0 font-weight:medium margin:u0 margin-bottom:u2 color:red">Red</h6>
<h6 class="font-height:0 font-weight:medium margin:u0 margin-bottom:u2 color:red-d1">Red Dark 1</h6>
<h6 class="font-height:0 font-weight:medium margin:u0 margin-bottom:u2 color:red-d2">Red Dark 2</h6>
<h6 class="font-height:0 font-weight:medium margin:u0 margin-bottom:u2 color:red-d3">Red Dark 3</h6>
<h6 class="font-height:0 font-weight:medium margin:u0 margin-bottom:u2 color:red-d4">Red Dark 4</h6>
<h6 class="font-height:0 font-weight:medium margin:u0 margin-bottom:u4 color:red-d5">Red Dark 5</h6>

```html
<h6 class="color:red-l5">Red Light 5</h6>
<h6 class="color:red-l4">Red Light 4</h6>
<h6 class="color:red-l3">Red Light 3</h6>
<h6 class="color:red-l2">Red Light 2</h6>
<h6 class="color:red-l1">Red Light 1</h6>
<h6 class="color:red">Red</h6>
<h6 class="color:red-d1">Red Dark 1</h6>
<h6 class="color:red-d2">Red Dark 2</h6>
<h6 class="color:red-d3">Red Dark 3</h6>
<h6 class="color:red-d4">Red Dark 4</h6>
<h6 class="color:red-d5">Red Dark 5</h6>
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
      <code>color</code>
    </td>
    <td data-label="Attributes">
      <code>:[base color]</code>
    </td>
    <td data-label="Responsive">
      No
    </td>
    <td>
      Apply defined color
    </td>
  </tr>
  <tr>
    <td data-label="Properties">
    </td>
    <td data-label="Attributes">
      <code class="margin:u0">:[base color]-l[1 - 5]</code><br>
      <code class="margin:u0">:[base color]-d[1 - 5]</code>
    </td>
    <td data-label="Responsive">
      No
    </td>
    <td>
      Apply light or dark tonal variants
    </td>
  </tr>
</table>
