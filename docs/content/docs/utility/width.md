+++
title = "Width"
date = "2018-04-11T09:16:45+12:00"
family = "Utility"
draft = false
description = "The width component adds width to any object or container."
+++

### Basic Usage

Defind with `width`. There are 18 levels of width which are based on the standard unit chart.

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="width:1"></div>
<div class="width:2"></div>
<div class="width:3"></div>
<div class="width:4"></div>
<div class="width:5"></div>
<div class="width:6"></div>
<div class="width:7"></div>
<div class="width:8"></div>
<div class="width:9"></div>
<div class="width:10"></div>
<div class="width:11"></div>
<div class="width:12"></div>
<div class="width:13"></div>
<div class="width:14"></div>
<div class="width:15"></div>
<div class="width:16"></div>
<div class="width:17"></div>
<div class="width:18"></div>
```
{{% /codeblock %}}

### Extra Modifiers

Full widths and default settings are also available.

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="width:100%"></div>
<div class="width:auto"></div>
```
{{% /codeblock %}}

### Responsive Margin

To apply responsive widthss add responsive suffixes

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="width@sm:10">
  ...
</div>
```
{{% /codeblock %}}

### Local Variables

You can override styling using the following local variables.

{{% codeblock key="language" definition="css" margin="bottom" %}}
```css
$widths: 18 !default;
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
      <code>width</code>
    </td>
    <td data-label="Attributes">
      <code>:1</code> ... <code>:18</code><br>
      <code>:100%</code> <code>:auto</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td class="row:reverse">
      Set width
    </td>
  </tr>
</table>
