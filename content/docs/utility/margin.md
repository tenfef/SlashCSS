+++
title = "Margin"
date = "2018-04-11T09:16:45+12:00"
draft = false
description = "The margin component adds margin to any object or container."
+++

### Basic Usage

Defind with `margin`. There are 16 levels of margin which are based on the standard unit chart.

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="margin:0"></div>
<div class="margin:1"></div>
<div class="margin:2"></div>
<div class="margin:3"></div>
<div class="margin:4"></div>
<div class="margin:5"></div>
<div class="margin:6"></div>
<div class="margin:7"></div>
<div class="margin:8"></div>
<div class="margin:9"></div>
<div class="margin:10"></div>
<div class="margin:11"></div>
<div class="margin:12"></div>
<div class="margin:13"></div>
<div class="margin:14"></div>
<div class="margin:15"></div>
```
{{% /codeblock %}}

### Directional Margin

Margin can be applied to `top` `right` `bottom` `left`.

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="margin-top:0"></div>
<div class="margin-right:1"></div>
<div class="margin-bottom:2"></div>
<div class="margin-left:3"></div>
```
{{% /codeblock %}}

### Responsive Margin

To apply responsive margins add responsive suffixes

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="margin@sm:2">
  ...
</div>
```
{{% /codeblock %}}

### Local Variables

You can override styling using the following local variables.

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
      <code>:0</code> ... <code>:15</code>
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
      <code>:0</code> ... <code>:15</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td class="row:reverse">
      Set directional margin
    </td>
  </tr>
</table>
