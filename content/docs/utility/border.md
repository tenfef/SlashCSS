+++
title = "Border"
date = "2018-04-11T09:16:45+12:00"
family = "Utility"
draft = false
description = "The Border component applies borders and corner radius properties to block elements."
+++

### Basic Usage

Defined with `border`. Default border color settings are applied.

<div class="border border-color:grey-l3 padding:6 fill:grey-l5 margin-bottom:6">
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="border">

</div>
```
{{% /codeblock %}}

### Positional Borders

You can apply positional borders.

<div class="border-top border-color:grey-l3 padding:6 fill:grey-l5 margin-bottom:6">
</div>

<div class="border-right border-color:grey-l3 padding:6 fill:grey-l5 margin-bottom:6">
</div>

<div class="border-bottom border-color:grey-l3 padding:6 fill:grey-l5 margin-bottom:6">
</div>

<div class="border-left border-color:grey-l3 padding:6 fill:grey-l5 margin-bottom:6">
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="border-top">
</div>

<div class="border-right">
</div>

<div class="border-bottom">
</div>

<div class="border-left">
</div>
```
{{% /codeblock %}}

### Corner Properties

You can apply various corner styles with the `border-radius` property. Positional corner styles are also available.

<div class="display:inline-block media-size:5 border-radius padding:6 fill:grey-l2 margin-bottom:6">
</div>

<div class="display:inline-block media-size:5 border-radius:round padding:6 fill:grey-l2 margin-bottom:6">
</div>

<div class="display:inline-block media-size:5 border-radius:sharp padding:6 fill:grey-l2 margin-bottom:6">
</div>

<div class="display:inline-block media-size:5 border-radius-left:round padding:6 fill:grey-l2 margin-bottom:6">
</div>

<div class="display:inline-block media-size:5 border-radius-right:round padding:6 fill:grey-l2 margin-bottom:6">
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="border-radius">
  ...
</div>
<div class="border-radius:round">
  ...
</div>
<div class="border-radius:sharp">
  ...
</div>
<div class="border-radius-left:round">
  ...
</div>
<div class="border-radius-right:round">
  ...
</div>
```
{{% /codeblock %}}

### Border Colors & Widths

You can change the color and width of your border with the `border-color` and `border-width` property.

<div class="border border-color:purple padding:6 fill:grey-l5 margin-bottom:6">
</div>

<div class="border-left border-color:orange border-width:5 border-radius elevate padding:6 fill:grey-l5 margin-bottom:6">
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="border border-color:purple">
  ...
</div>

<div class="border-left border-color:orange border-width:5 border-radius elevate">
  ...
</div>
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
      <code>border</code><span class="color:orange">&#42;</span>
    </td>
    <td data-label="Attributes">
      <code>:none</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td class="row:reverse">
      Apply or remove border
    </td>
  </tr>
  <tr>
    <td data-label="Properties">
      <code>border-[position]</code><span class="color:orange">&#42;</span>
    </td>
    <td data-label="Attributes">
      <code>:none</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td class="row:reverse">
      Apply or remove directional border
    </td>
  </tr>
  <tr>
    <td data-label="Properties">
      <code>border-radius</code><span class="color:orange">&#42;</span>
    </td>
    <td data-label="Attributes">
      <code>:sharp</code> <code>:round</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td class="row:reverse">
      Apply various corner styles
    </td>
  </tr>
  <tr>
    <td data-label="Properties">
      <code>border-radius-[position]</code><span class="color:orange">&#42;</span>
    </td>
    <td data-label="Attributes">
      <code>:sharp</code> <code>:round</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td class="row:reverse">
      Apply positional corner styles
    </td>
  </tr>
  <tr>
    <td data-label="Properties">
      <code>border-color</code>
    </td>
    <td data-label="Attributes">
      <code>:red</code> ... <code>:black</code>
    </td>
    <td data-label="Responsive">
      No
    </td>
    <td class="row:reverse">
      Control border color
    </td>
  </tr>
  <tr>
    <td data-label="Properties">
      <code>border-width</code>
    </td>
    <td data-label="Attributes">
      <code>:1</code> ... <code>:5</code>
    </td>
    <td data-label="Responsive">
      No
    </td>
    <td class="row:reverse">
      Control border width
    </td>
  </tr>
</table>
<p class="margin-top:2 font-size:tiny color:orange">
  &#42; These properties have a default values set when used without modifiers.
</p>
