+++
title = "Hover"
date = "2018-04-11T09:16:45+12:00"
family = "Utility"
draft = false
description = "The hover component provides easy way to apply hover states to an object or container."
+++

### Basic Usage

Defind with `hover`. The default hover class provides pointer cursor and transition to the applied element

<span class="hover padding:u4 margin-bottom:u6">Hover me</span>
<span class="hover padding:u4 hover:underline margin-bottom:u6">Hover me</span>
<span class="hover padding:u4 hover:elevate margin-bottom:u6">Hover me</span>

```html
<span class="hover">Hover me</span>
<span class="hover hover:underline">Hover me</span>
<span class="hover hover:elevate">Hover me</span>
```

### Hover Fill

Apply hover fills with `hover-fill` property. All base and tonal colors are available.

<div class="display:inline-flex padding:u2 border margin-bottom:u6 hover hover-fill:grey-l4">
  Hover Fill
</div>

```html
<div class="hover hover-fill:grey-l4">
  Hover Fill
</div>
```

### Hover Color

Apply hover colors with `hover-color` property. All base and tonal colors are available.

<p class="margin-bottom:u6 color:grey hover hover-color:grey-d4">
  Hover Color
</p>

```html
<p class="hover hover-color:grey-d4">
  Hover Color
</p>
```

### Hover Opacity

Apply hover opacities with `hover-opacity` property.

<p class="color:grey hover hover-opacity:5">
  Hover Opacity
</p>

```html
<p class="hover hover-opacity:5">
  Hover Color
</p>
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
      <code>hover</code><span class="color:orange">&#42;</span>
    </td>
    <td data-label="Attributes">
      <code>:underline</code> <code>:elevate</code>
    </td>
    <td data-label="Responsive">
      No
    </td>
    <td>
      Set hover states
    </td>
  </tr>
  <tr>
    <td data-label="Properties">
      <code>hover-fill</code>
    </td>
    <td data-label="Attributes">
      <code>:[color]</code>
    </td>
    <td data-label="Responsive">
      No
    </td>
    <td>
      Set hover fill
    </td>
  </tr>
  <tr>
    <td data-label="Properties">
      <code>hover-color</code>
    </td>
    <td data-label="Attributes">
      <code>:[color]</code>
    </td>
    <td data-label="Responsive">
      No
    </td>
    <td>
      Set hover colors
    </td>
  </tr>
  <tr>
    <td data-label="Properties">
      <code>hover-opacity</code>
    </td>
    <td data-label="Attributes">
      <code>:0</code> <code>:10</code>
    </td>
    <td data-label="Responsive">
      No
    </td>
    <td>
      Set hover opacity
    </td>
  </tr>
</table>
<p class="margin-top:2 font-size:tiny color:orange">
  &#42; These properties have a default values set when used without modifiers.
</p>
