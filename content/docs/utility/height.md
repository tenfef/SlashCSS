+++
title = "Height"
date = "2018-04-11T09:16:45+12:00"
draft = false
description = "The height component adds height to any object or container."
+++

##### Basic Usage

Defind with `height`. There are 18 levels of height which are based on the standard unit chart.

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="height:1"></div>
<div class="height:2"></div>
<div class="height:3"></div>
<div class="height:4"></div>
<div class="height:5"></div>
<div class="height:6"></div>
<div class="height:7"></div>
<div class="height:8"></div>
<div class="height:9"></div>
<div class="height:10"></div>
<div class="height:11"></div>
<div class="height:12"></div>
<div class="height:13"></div>
<div class="height:14"></div>
<div class="height:15"></div>
<div class="height:16"></div>
<div class="height:17"></div>
<div class="height:18"></div>
```
{{% /codeblock %}}

##### Extra Modifiers

Full heights and default settings are also available.

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="height:100%"></div>
<div class="height:auto"></div>
```
{{% /codeblock %}}

##### Responsive Margin

To apply responsive heightss add responsive suffixes

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="height@sm:10">
  ...
</div>
```
{{% /codeblock %}}

##### Local Variables

You can override styling using the following local variables.

{{% codeblock key="language" definition="css" margin="bottom" %}}
```css
$heights: 18 !default;
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
      <code>height</code>
    </td>
    <td data-label="Attributes">
      <code>:1</code> ... <code>:18</code><br>
      <code>:100%</code> <code>:auto</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td class="row:reverse">
      Set height
    </td>
  </tr>
</table>
