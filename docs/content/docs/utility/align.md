+++
title = "Align"
date = "2018-04-11T09:16:45+12:00"
family = "Utility"
draft = false
description = "The align component sets the alignment of content in various ways."
+++

### Text Alignment

The basic `align` property controls text alignment.

<div class="margin-bottom:u6 fill:grey-l4">
  <div class="align:left">Left Aligned</div>
  <div class="align:center">Center Aligned</div>
  <div class="align:right">Right Aligned</div>
</div>

```html
<div class="align:left">Left</div>
<div class="align:center">Center</div>
<div class="align:right">Right</div>
```

### Vertical Alignment

Vertical alignment can be controlled with `top` `middle` `bottom` modifiers.

<div class="row row-gutter:2">
  <div class="column font-size:h1 margin-bottom:u6">
    <div class="fill:grey-l4">
      <div class="media media-size:sm display:inline-block fill:grey-l2 color:white align:top"></div>
    </div>
  </div>

  <div class="column font-size:h1 margin-bottom:u6">
    <div class="fill:grey-l4">
      <div class="media media-size:sm display:inline-block fill:grey-l2 color:white align:middle"></div>
    </div>
  </div>

  <div class="column font-size:h1 margin-bottom:u6">
    <div class="fill:grey-l4">
      <div class="media media-size:sm display:inline-block fill:grey-l2 color:white align:bottom"></div>
    </div>
  </div>
</div>
```html
<div class="align:top"></div>
<div class="align:middle"></div>
<div class="align:bottom"></div>
```

### Responsive Alignments

Responsive suffixes can be applied to all alignment properties.

<div class="margin-bottom:u6 fill:grey-l4">
  <div class="align:left">Left</div>
  <div class="align@md:center">Center</div>
  <div class="align@lg:right">Large</div>
</div>

```html
<div class="align:left">Left</div>
<div class="align@md:center">Center</div>
<div class="align@lg:right">Large</div>
```

### Item Alignment

The `align-items` property specifies the default alignment for items inside the flexible container. The `align-content` property is also available and can be used in a similar way.

<div class="row row-gutter:u2 margin-bottom:u6">
  <div class="column:4 flex align-items:start height:u10">
    <div class="padding:u4 color:white fill:grey-l2"></div>
  </div>
  <div class="column:4 flex align-items:center height:u10">
    <div class="padding:u4 color:white fill:grey-l2"></div>
  </div>
  <div class="column:4 flex align-items:end height:u10">
    <div class="padding:u4 color:white fill:grey-l2"></div>
  </div>
</div>

```html
<div class="align-items:top">
  ...
</div>
<div class="align-items:middle">
  ...
</div>
<div class="align-items:bottom">
  ...
</div>
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
      <code>align</code>
    </td>
    <td data-label="Attributes">
      <code>:top</code> <code>:middle</code> <code>:bottom</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td class="row:reverse">
      Set vertical aligment
    </td>
  </tr>
  <tr>
    <td data-label="Properties">
    </td>
    <td data-label="Attributes">
      <code>:left</code> <code>:center</code> <code>:right</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td class="row:reverse">
      Set text alignment
    </td>
  </tr>
  <tr>
    <td data-label="Properties">
      <code>align-content</code><span class="color:orange">&#42;</span>
    </td>
    <td data-label="Attributes">
      <code>:start</code> <code>:center</code> <code>:end</code> <code>:between</code> <code>:around</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td class="row:reverse">
      Set flexible content alignment
    </td>
  </tr>
  <tr>
    <td data-label="Properties">
      <code>align-items</code><span class="color:orange">&#42;</span>
    </td>
    <td data-label="Attributes">
      <code>:start</code> <code>:center</code> <code>:end</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td class="row:reverse">
      Set alignement of flexible items
    </td>
  </tr>
</table>
<p class="margin-top:2 font-size:tiny color:orange">
  &#42; These properties have a default values set when used without modifiers.
</p>
