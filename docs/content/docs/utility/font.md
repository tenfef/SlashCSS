+++
title = "Font"
date = "2018-04-11T09:16:45+12:00"
family = "Utility"
draft = false
description = "The font component provides useful ways of styling text."
+++

### Font Sizes

The `font-size` property has 9 sizes.

<p class="font-size:hero font-height:1">Hero Typography</p>
<p class="font-size:h1 font-height:1">H1 Typography</p>
<p class="font-size:h2 font-height:1">h2 Typography</p>
<p class="font-size:h3 font-height:1">H3 Typography</p>
<p class="font-size:h4 font-height:1">H4 Typography</p>
<p class="font-size:h5 font-height:1">H5 Typography</p>
<p class="font-size:h6 font-height:1">H6 Typography</p>
<p class="font-size:body font-height:1">Body</p>
<p class="font-size:tiny font-height:1">Tiny</p>
<p class="font-size:micro font-height:1">Micro</p>

```html
<p class="font-size:hero">Hero Typography</p>
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

### Weights

For different weights use standard weight modifiers.

<h3 class="font-weight:light font-height:1.4 margin:u0">Light Typography</h3>
<h3 class="font-weight:regular font-height:1.4 margin:u0">Regular Typography</h3>
<h3 class="font-weight:medium font-height:1.4 margin:u0">Medium Typography</h3>
<h3 class="font-weight:bold font-height:1.4 margin:u0">Bold Typography</h3>

```html
<h3 class="font-weight:light">Light Typography</h3>
<h3 class="font-weight:regular">Regular Typography</h3>
<h3 class="font-weight:medium">Medium Typography</h3>
<h3 class="font-weight:bold">Bold Typography</h3>
```

### Line Height

You can apply unitless line height with the `font-height` property.

<h6 class="font-height:1 fill:grey-l4 margin:u0 margin-bottom:u2">Line Height 1</h6>
<h6 class="font-height:1.1 fill:grey-l4 margin:u0 margin-bottom:u2">Line Height 1.1</h6>
<h6 class="font-height:1.2 fill:grey-l4 margin:u0 margin-bottom:u2">Line Height 1.2</h6>
<h6 class="font-height:1.3 fill:grey-l4 margin:u0 margin-bottom:u2">Line Height 1.3</h6>
<h6 class="font-height:1.4 fill:grey-l4 margin:u0 margin-bottom:u2">Line Height 1.4</h6>
<h6 class="font-height:1.5 fill:grey-l4 margin:u0 margin-bottom:u4">Line Height 1.5</h6>
<h6 class="font-height:1.6 fill:grey-l4 margin:u0 margin-bottom:u4">Line Height 1.6</h6>

```html
<h6 class="font-height:1">Line Height 1</h6>
<h6 class="font-height:1.1">Line Height 1.1</h6>
<h6 class="font-height:1.2">Line Height 1.2</h6>
<h6 class="font-height:1.3">Line Height 1.3</h6>
<h6 class="font-height:1.4">Line Height 1.4</h6>
<h6 class="font-height:1.5">Line Height 1.5</h6>
<h6 class="font-height:1.6">Line Height 1.5</h6>
```

### Font Transform

You can transform capitalization of your text with the `font-case` property.

```html
<h6 class="font-case:none">No Transform</h6>
<h6 class="font-case:upper">Uppercase</h6>
<h6 class="font-case:lower">Lowercase</h6>
```

### Local Variables

You can override this component using the following local variables.

```css
$font-heights: 6 !default;
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
      <code>font-size</code>
    </td>
    <td data-label="Attributes">
      <code>:hero</code><br>
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
    <td>
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
      <code>:bold</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td>
      Set font weight
    </td>
  </tr>
  <tr>
    <td data-label="Properties">
      <code>font-height</code>
    </td>
    <td data-label="Attributes">
      <code>:1</code> ... <code>:6</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td>
      Set line height
    </td>
  </tr>
  <tr>
    <td data-label="Properties">
      <code>font-case</code>
    </td>
    <td data-label="Attributes">
      <code>:none</code> <code>:upper</code> <code>:lower</code>
    </td>
    <td data-label="Responsive">
      No
    </td>
    <td>
      Set text transform
    </td>
  </tr>
</table>
