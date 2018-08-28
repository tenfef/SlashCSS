+++
title = "Margin"
date = "2018-04-11T09:16:45+12:00"
family = "Utility"
draft = false
description = "The margin component adds margin to any object or container."
+++

### Basic Usage

Defind with `margin`. There are 16 levels of margin which are based on the standard unit chart.

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="margin:u0"></div>
<div class="margin:u1"></div>
<div class="margin:u2"></div>
<div class="margin:u3"></div>
<div class="margin:u4"></div>
<div class="margin:u5"></div>
<div class="margin:u6"></div>
<div class="margin:u7"></div>
<div class="margin:u8"></div>
<div class="margin:u9"></div>
<div class="margin:u10"></div>
<div class="margin:u11"></div>
<div class="margin:u12"></div>
<div class="margin:u13"></div>
<div class="margin:u14"></div>
<div class="margin:u15"></div>
```
{{% /codeblock %}}

### Directional Margin

Margin can be applied to `top` `right` `bottom` `left`.

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="margin-top:0"></div>
<div class="margin-right:u1"></div>
<div class="margin-bottom:u2"></div>
<div class="margin-left:u3"></div>
```
{{% /codeblock %}}

### Responsive Margin

To apply responsive margins add responsive suffixes

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="margin@sm:u2">
  ...
</div>
```
{{% /codeblock %}}

### Local Variables

You can override this component using the following local variables.

{{% codeblock key="language" definition="css" margin="bottom" %}}
```css
$margins: 15 !default;
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
      <code>margin</code>
    </td>
    <td data-label="Attributes">
      <code>:0</code> <code>:u1</code> ... <code>:u15</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td class="row:reverse">
      Set margin
    </td>
  </tr>
  <tr>
    <td data-label="Properties">
      <code>margin-[direction]</code>
    </td>
    <td data-label="Attributes">
      <code>:0</code> <code>:u1</code> ... <code>:u15</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td class="row:reverse">
      Set directional margin
    </td>
  </tr>
</table>
