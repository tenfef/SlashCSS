+++
title = "Font"
date = "2018-04-11T09:16:45+12:00"
draft = false
description = "The font component provides useful ways of styling text."
+++

### Font Sizes

The `font-size` property has 9 sizes.

<p class="font-size:h1 font-height:0">H1 Typography</p>
<p class="font-size:h2 font-height:0">h2 Typography</p>
<p class="font-size:h3 font-height:0">H3 Typography</p>
<p class="font-size:h4 font-height:0">H4 Typography</p>
<p class="font-size:h5 font-height:0">H5 Typography</p>
<p class="font-size:h6 font-height:0">H6 Typography</p>
<p class="font-size:body font-height:0">Body</p>
<p class="font-size:tiny font-height:0">Tiny</p>
<p class="font-size:micro font-height:0">Micro</p>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<p class="font-size:h1">H1 Typography</p>
<p class="font-size:h2">h2 Typography</p>
<p class="font-size:h3">H3 Typography</p>
<p class="font-size:h4">H4 Typography</p>
<p class="font-size:h5">H5 Typography</p>
<p class="font-size:h6">H6 Typography</p>
<p class="font-size:body">Body</p>
<p class="font-size:tiny">Tiny</p>
<p class="font-size:micro">Micro</p>
```
{{% /codeblock %}}

### Weights

For different weights use standard weight modifiers.

<h3 class="font-weight:light font-height:4 margin:0">Light Typography</h3>
<h3 class="font-weight:regular font-height:4 margin:0">Regular Typography</h3>
<h3 class="font-weight:medium font-height:4 margin:0">Medium Typography</h3>
<h3 class="font-weight:bold font-height:4 margin:0">Bold Typography</h3>
<h3 class="font-weight:black font-height:4 margin:0 margin-bottom:4">Black Typography</h3>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<h3 class="font-weight:light">Light Typography</h3>
<h3 class="font-weight:regular">Regular Typography</h3>
<h3 class="font-weight:medium">Medium Typography</h3>
<h3 class="font-weight:bold">Bold Typography</h3>
<h3 class="font-weight:black">Black Typography</h3>
```
{{% /codeblock %}}

### Line Height

You can apply unitless line height with the `font-height` property.

<h6 class="font-height:0 fill:grey-l4 margin:0 margin-bottom:1">Line Height 1</h6>
<h6 class="font-height:1 fill:grey-l4 margin:0 margin-bottom:1">Line Height 1.1</h6>
<h6 class="font-height:2 fill:grey-l4 margin:0 margin-bottom:1">Line Height 1.2</h6>
<h6 class="font-height:3 fill:grey-l4 margin:0 margin-bottom:1">Line Height 1.3</h6>
<h6 class="font-height:4 fill:grey-l4 margin:0 margin-bottom:1">Line Height 1.4</h6>
<h6 class="font-height:5 fill:grey-l4 margin:0 margin-bottom:4">Line Height 1.5</h6>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<h6 class="font-height:0">Line Height 1</h6>
<h6 class="font-height:1">Line Height 1.1</h6>
<h6 class="font-height:2">Line Height 1.2</h6>
<h6 class="font-height:3">Line Height 1.3</h6>
<h6 class="font-height:4">Line Height 1.4</h6>
<h6 class="font-height:5">Line Height 1.5</h6>
```
{{% /codeblock %}}

### Font Transform

You can transform capitalization of your text with the `font-transform` property.


{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<h6 class="font-transform:none">No Transform</h6>
<h6 class="font-transform:upper">Uppercase</h6>
<h6 class="fonttranform:lower">Lowercase</h6>
```
{{% /codeblock %}}

### Local Variables

You can override styling using the following local variables.

{{% codeblock key="language" definition="css" margin="bottom" %}}
```css
$font-heights: 5 !default;
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
      <code>font-size</code>
    </td>
    <td data-label="Attributes">
      <code>:h1</code><br>
      <code>:h2</code><br>
      <code>:h3</code><br>
      <code>:h4</code><br>
      <code>:h5</code><br>
      <code>:h6</code><br>
      <code>:body</code><br>
      <code>:tiny</code><br>
      <code>:micro</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td class="row:reverse">
      Set font size
    </td>
  </tr>
  <tr>
    <td data-label="Properties">
      <code>font-size</code>
    </td>
    <td data-label="Attributes">
      <code>:h1</code><br>
      <code>:h2</code><br>
      <code>:h3</code><br>
      <code>:h4</code><br>
      <code>:h5</code><br>
      <code>:h6</code><br>
      <code>:body</code><br>
      <code>:tiny</code><br>
      <code>:micro</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td class="row:reverse">
      Set font size
    </td>
  </tr>
  <tr>
    <td data-label="Properties">
      <code>font-weight</code>
    </td>
    <td data-label="Attributes">
      <code>:light</code><br>
      <code>:regular</code><br>
      <code>:medium</code><br>
      <code>:bold</code><br>
      <code>:black</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td class="row:reverse">
      Set font weight
    </td>
  </tr>
  <tr>
    <td data-label="Properties">
      <code>font-height</code>
    </td>
    <td data-label="Attributes">
      <code>:1</code> ... <code>:5</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td class="row:reverse">
      Set line height
    </td>
  </tr>
  <tr>
    <td data-label="Properties">
      <code>font-transform</code>
    </td>
    <td data-label="Attributes">
      <code>:none</code> <code>:upper</code> <code>:lower</code>
    </td>
    <td data-label="Responsive">
      No
    </td>
    <td class="row:reverse">
      Set text transform
    </td>
  </tr>
</table>
