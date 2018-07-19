+++
title = "Hover"
date = "2018-04-11T09:16:45+12:00"
draft = false
description = "The hover component provides easy way to apply hover states to an object or container."
+++

##### Basic Usage

Defind with `hover`. The default hover class provides pointer cursor and transition to the applied element

<span class="padding:1 hover margin-bottom:6">Hover me</span>
<span class="padding:1 hover hover:underline margin-bottom:6">Hover me</span>
<span class="padding:1 hover hover:elevate margin-bottom:6">Hover me</span>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<span class="hover">Hover me</span>
<span class="hover hover:underline">Hover me</span>
<span class="hover hover:elevate">Hover me</span>
```
{{% /codeblock %}}

##### Hover Fill

Apply hover fills with `hover-fill` property. All base and tonal colors are available.

<div class="display:inline-flex padding:2 border margin-bottom:6 hover hover-fill:grey-l4">
  Hover Fill
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="hover hover-fill:grey-l4">
  Hover Fill
</div>
```
{{% /codeblock %}}

##### Hover Color

Apply hover colors with `hover-color` property. All base and tonal colors are available.

<p class="margin-bottom:6 color:grey hover hover-color:grey-d4">
  Hover Color
</p>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<p class="hover hover-color:grey-d4">
  Hover Color
</p>
```
{{% /codeblock %}}

##### Hover Opacity

Apply hover opacities with `hover-opacity` property.

<p class="margin-bottom:6 color:grey hover hover-opacity:5">
  Hover Opacity
</p>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<p class="hover hover-opacity:5">
  Hover Color
</p>
```
{{% /codeblock %}}

##### Options

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
    <td class="row:reverse">
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
    <td class="row:reverse">
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
    <td class="row:reverse">
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
    <td class="row:reverse">
      Set hover opacity
    </td>
  </tr>
</table>
<p class="margin-top:2 font-size:tiny color:orange">
  &#42; These properties have a default values set when used without modifiers.
</p>
