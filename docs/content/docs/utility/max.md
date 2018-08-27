+++
title = "Max"
date = "2018-04-11T09:16:45+12:00"
family = "Utility"
draft = false
description = "The max component provides max width or max height properties."
+++

### Basic Usage

Defind with `max-width` and `max-height`. There are 18 levels of max-height which are based on the standard unit chart.

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="max-width:1"></div>
<div class="max-width:2"></div>
<div class="max-width:3"></div>
<div class="max-width:4"></div>
<div class="max-width:5"></div>
<div class="max-width:6"></div>
<div class="max-width:7"></div>
<div class="max-width:8"></div>
<div class="max-width:9"></div>
<div class="max-width:10"></div>
<div class="max-width:11"></div>
<div class="max-width:12"></div>
<div class="max-width:13"></div>
<div class="max-width:14"></div>
<div class="max-width:15"></div>
<div class="max-width:16"></div>
<div class="max-width:17"></div>
<div class="max-width:18"></div>

<div class="max-height:1"></div>
<div class="max-height:2"></div>
<div class="max-height:3"></div>
<div class="max-height:4"></div>
<div class="max-height:5"></div>
<div class="max-height:6"></div>
<div class="max-height:7"></div>
<div class="max-height:8"></div>
<div class="max-height:9"></div>
<div class="max-height:10"></div>
<div class="max-height:11"></div>
<div class="max-height:12"></div>
<div class="max-height:13"></div>
<div class="max-height:14"></div>
<div class="max-height:15"></div>
<div class="max-height:16"></div>
<div class="max-height:17"></div>
<div class="max-height:18"></div>
```
{{% /codeblock %}}

### Fluid Modifiers

Widths and heights can be fluid.

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="max-width:100%"></div>
<div class="max-height:100%"></div>
```
{{% /codeblock %}}

### Responsive Properties

To apply responsive max-heights add responsive suffixes

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="max-height@md:1"></div>
<div class="max-height@lg:4"></div>
```
{{% /codeblock %}}

### Local Variables

You can override styling using the following local variables.

{{% codeblock key="language" definition="css" margin="bottom" %}}
```css
$max-levels: 18 !default;
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
      <code>max-width</code>
    </td>
    <td data-label="Attributes">
      <code>:1</code> ... <code>:18</code> <code>100%</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td class="row:reverse">
      Set max width
    </td>
  </tr>
  <tr>
    <td data-label="Properties">
      <code>max-height</code>
    </td>
    <td data-label="Attributes">
      <code>:1</code> ... <code>:18</code> <code>100%</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td class="row:reverse">
      Set max height
    </td>
  </tr>
</table>
