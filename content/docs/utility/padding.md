+++
title = "Padding"
date = "2018-04-11T09:16:45+12:00"
family = "Utility"
draft = false
description = "The padding component adds padding to any object or container."
+++

### Basic Usage

Defind with `padding`. There are 16 levels of padding which are based on the standard unit chart.

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="padding:0"></div>
<div class="padding:1"></div>
<div class="padding:2"></div>
<div class="padding:3"></div>
<div class="padding:4"></div>
<div class="padding:5"></div>
<div class="padding:6"></div>
<div class="padding:7"></div>
<div class="padding:8"></div>
<div class="padding:9"></div>
<div class="padding:10"></div>
<div class="padding:11"></div>
<div class="padding:12"></div>
<div class="padding:13"></div>
<div class="padding:14"></div>
<div class="padding:15"></div>
```
{{% /codeblock %}}

### Directional Padding

Margin can be applied to `top` `right` `bottom` `left`. It can also be applied to only the horizontal and vertical axis.

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="padding-top:0"></div>
<div class="padding-right:1"></div>
<div class="padding-bottom:2"></div>
<div class="padding-left:3"></div>
<div class="padding-x:4"></div>
<div class="padding-y:5"></div>
```
{{% /codeblock %}}

### Responsive Padding

To apply responsive paddings add responsive suffixes

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="padding@sm:2">
  ...
</div>
<div class="padding-y@lg:5">
  ...
</div>
```
{{% /codeblock %}}

### Viewport Padding

Unlike the margin component, the padding component also supports viewport height based paddings.

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="padding-top:10vh">
  ...
</div>
<div class="padding-right@md:5vh">
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
      <code>padding</code>
    </td>
    <td data-label="Attributes">
      <code>:0</code> ... <code>:15</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td class="row:reverse">
      Set padding
    </td>
  </tr>
  <tr>
    <td data-label="Properties">
      <code>padding-[direction]</code>
    </td>
    <td data-label="Attributes">
      <code>:0</code> ... <code>:15</code><br>
      <code>:5vh</code> ... <code>:15vh</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td class="row:reverse">
      Set directional padding
    </td>
  </tr>
  <tr>
    <td data-label="Properties">
      <code>padding-[x/y]</code>
    </td>
    <td data-label="Attributes">
      <code>:0</code> ... <code>:15</code><br>
      <code>:5vh</code> ... <code>:15vh</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td class="row:reverse">
      Set horizontal or vertical padding
    </td>
  </tr>
</table>
