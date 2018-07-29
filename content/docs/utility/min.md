+++
title = "Min"
date = "2018-04-11T09:16:45+12:00"
family = "Utility"
draft = false
description = "The min component provides min width or min height properties."
+++

### Basic Usage

Defind with `min-width` and `min-height`. There are 18 levels of min-height which are based on the standard unit chart.

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="min-width:1"></div>
<div class="min-width:2"></div>
<div class="min-width:3"></div>
<div class="min-width:4"></div>
<div class="min-width:5"></div>
<div class="min-width:6"></div>
<div class="min-width:7"></div>
<div class="min-width:8"></div>
<div class="min-width:9"></div>
<div class="min-width:10"></div>
<div class="min-width:11"></div>
<div class="min-width:12"></div>
<div class="min-width:13"></div>
<div class="min-width:14"></div>
<div class="min-width:15"></div>
<div class="min-width:16"></div>
<div class="min-width:17"></div>
<div class="min-width:18"></div>

<div class="min-height:1"></div>
<div class="min-height:2"></div>
<div class="min-height:3"></div>
<div class="min-height:4"></div>
<div class="min-height:5"></div>
<div class="min-height:6"></div>
<div class="min-height:7"></div>
<div class="min-height:8"></div>
<div class="min-height:9"></div>
<div class="min-height:10"></div>
<div class="min-height:11"></div>
<div class="min-height:12"></div>
<div class="min-height:13"></div>
<div class="min-height:14"></div>
<div class="min-height:15"></div>
<div class="min-height:16"></div>
<div class="min-height:17"></div>
<div class="min-height:18"></div>
```
{{% /codeblock %}}

### Fluid Modifiers

Widths and heights can be fluid.

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="min-width:100%"></div>
<div class="min-height:100%"></div>
```
{{% /codeblock %}}

### Responsive Properties

To apply responsive min-heights add responsive suffixes

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="min-height@md:1"></div>
<div class="min-height@lg:4"></div>
```
{{% /codeblock %}}

### Local Variables

You can override styling using the following local variables.

{{% codeblock key="language" definition="css" margin="bottom" %}}
```css
$min-levels: 18 !default;
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
      <code>min-width</code>
    </td>
    <td data-label="Attributes">
      <code>:1</code> ... <code>:18</code> <code>100%</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td class="row:reverse">
      Set min width
    </td>
  </tr>
  <tr>
    <td data-label="Properties">
      <code>min-height</code>
    </td>
    <td data-label="Attributes">
      <code>:1</code> ... <code>:18</code> <code>100%</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td class="row:reverse">
      Set min height
    </td>
  </tr>
</table>
