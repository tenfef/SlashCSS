+++
title = "Align"
date = "2018-04-11T09:16:45+12:00"
draft = false
description = "The align component sets the alignment of content in various ways."
+++

##### Text Alignment

The basic `align` property controls text alignment.

<div class="margin-bottom:2 fill:grey-l4">
  <div class="align:left">Left Aligned</div>
  <div class="align:center">Center Aligned</div>
  <div class="align:right">Right Aligned</div>
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="align:left">Left</div>
<div class="align:center">Center</div>
<div class="align:right">Right</div>
```
{{% /codeblock %}}

##### Vertical Alignment

Vertical alignment can be controlled with `top` `middle` `bottom` modifiers.

<div class="row row-gutter:2">
  <div class="column font-size:h3 margin-bottom:2">
    <div class="fill:grey-l4">
      <div class="image image-size:2 display:inline-block fill:grey-l2 color:white align:top"></div>
    </div>
  </div>

  <div class="column font-size:h3 margin-bottom:2">
    <div class="fill:grey-l4">
      <div class="image image-size:2 display:inline-block fill:grey-l2 color:white align:middle"></div>
    </div>
  </div>

  <div class="column font-size:h3 margin-bottom:2">
    <div class="fill:grey-l4">
      <div class="image image-size:2 display:inline-block fill:grey-l2 color:white align:bottom"></div>
    </div>
  </div>
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="align:top"></div>
<div class="align:middle"></div>
<div class="align:bottom"></div>
```
{{% /codeblock %}}

##### Responsive Alignments

Responsive suffixes can be applied to all alignment properties.

<div class="margin-bottom:2 fill:grey-l4">
  <div class="align:left">Left</div>
  <div class="align@md:center">Center</div>
  <div class="align@lg:right">Large</div>
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="align:left">Left</div>
<div class="align@md:center">Center</div>
<div class="align@lg:right">Large</div>
```
{{% /codeblock %}}

##### Item Alignment

The `align-items` property specifies the default alignment for items inside the flexible container.

<div class="row row-gutter:2 margin-bottom:2">
  <div class="column:3">
    <div class="display:flex height:10 fill:grey-l4 align-items:top">
      <div class="padding:2 color:white fill:grey-l2"></div>
    </div>
  </div>
  <div class="column:3">
    <div class="display:flex height:10 fill:grey-l4 align-items:middle">
      <div class="padding:2 color:white fill:grey-l2"></div>
    </div>
  </div>
  <div class="column:3">
    <div class="display:flex height:10 fill:grey-l4 align-items:bottom">
      <div class="padding:2 color:white fill:grey-l2"></div>
    </div>
  </div>
  <div class="column:3">
    <div class="display:flex height:10 fill:grey-l4 align-items:baseline">
      <div class="column:4 align:center color:white fill:grey-l2">&nbsp;</div>
      <div class="column:4 padding-y:2 align:center color:white fill:grey-l2">&nbsp;</div>
      <div class="column:4 align:center color:white fill:grey-l2">&nbsp;</div>
    </div>
  </div>
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
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
<div class="align-items:baseline">
  ...
</div>
```
{{% /codeblock %}}


##### Content Alignment

The `align-content` property modifies the behavior of the flex-wrap property. It is similar to align-items, but instead of aligning flex items, it aligns flex lines. The align content property also controls justification of flexible content.

<div class="row row-gutter:2 margin-bottom:2">
  <div class="column margin-bottom:2" style="width: 20%;">
    <div class="display:flex flex-wrap height:20 fill:grey-l4 align-content:top">
      <div class="column:4 padding:1">
        <div class="fill:grey-l2">
          &nbsp;
        </div>
      </div>
      <div class="column:4 padding:1">
        <div class="fill:grey-l2">
          &nbsp;
        </div>
      </div>
      <div class="column:4 padding:1">
        <div class="fill:grey-l2">
          &nbsp;
        </div>
      </div>
      <div class="column:4 padding:1">
        <div class="fill:grey-l2">
          &nbsp;
        </div>
      </div>
      <div class="column:4 padding:1">
        <div class="fill:grey-l2">
          &nbsp;
        </div>
      </div>
      <div class="column:4 padding:1">
        <div class="fill:grey-l2">
          &nbsp;
        </div>
      </div>
    </div>
  </div>
  <div class="column margin-bottom:2" style="width: 20%;">
    <div class="display:flex flex-wrap height:20 fill:grey-l4 align-content:middle">
      <div class="column:4 padding:1">
        <div class="fill:grey-l2">
          &nbsp;
        </div>
      </div>
      <div class="column:4 padding:1">
        <div class="fill:grey-l2">
          &nbsp;
        </div>
      </div>
      <div class="column:4 padding:1">
        <div class="fill:grey-l2">
          &nbsp;
        </div>
      </div>
      <div class="column:4 padding:1">
        <div class="fill:grey-l2">
          &nbsp;
        </div>
      </div>
      <div class="column:4 padding:1">
        <div class="fill:grey-l2">
          &nbsp;
        </div>
      </div>
      <div class="column:4 padding:1">
        <div class="fill:grey-l2">
          &nbsp;
        </div>
      </div>
    </div>
  </div>
  <div class="column margin-bottom:2" style="width: 20%;">
    <div class="display:flex flex-wrap height:20 fill:grey-l4 align-content:bottom">
      <div class="column:4 padding:1">
        <div class="fill:grey-l2">
          &nbsp;
        </div>
      </div>
      <div class="column:4 padding:1">
        <div class="fill:grey-l2">
          &nbsp;
        </div>
      </div>
      <div class="column:4 padding:1">
        <div class="fill:grey-l2">
          &nbsp;
        </div>
      </div>
      <div class="column:4 padding:1">
        <div class="fill:grey-l2">
          &nbsp;
        </div>
      </div>
      <div class="column:4 padding:1">
        <div class="fill:grey-l2">
          &nbsp;
        </div>
      </div>
      <div class="column:4 padding:1">
        <div class="fill:grey-l2">
          &nbsp;
        </div>
      </div>
    </div>
  </div>
  <div class="column margin-bottom:2" style="width: 20%;">
    <div class="display:flex flex-wrap height:20 fill:grey-l4 align-content-y:between">
      <div class="column:4 padding:1">
        <div class="fill:grey-l2">
          &nbsp;
        </div>
      </div>
      <div class="column:4 padding:1">
        <div class="fill:grey-l2">
          &nbsp;
        </div>
      </div>
      <div class="column:4 padding:1">
        <div class="fill:grey-l2">
          &nbsp;
        </div>
      </div>
      <div class="column:4 padding:1">
        <div class="fill:grey-l2">
          &nbsp;
        </div>
      </div>
      <div class="column:4 padding:1">
        <div class="fill:grey-l2">
          &nbsp;
        </div>
      </div>
      <div class="column:4 padding:1">
        <div class="fill:grey-l2">
          &nbsp;
        </div>
      </div>
    </div>
  </div>
  <div class="column margin-bottom:2" style="width: 20%;">
    <div class="display:flex flex-wrap height:20 fill:grey-l4 align-content-y:around">
      <div class="column:4 padding:1">
        <div class="fill:grey-l2">
          &nbsp;
        </div>
      </div>
      <div class="column:4 padding:1">
        <div class="fill:grey-l2">
          &nbsp;
        </div>
      </div>
      <div class="column:4 padding:1">
        <div class="fill:grey-l2">
          &nbsp;
        </div>
      </div>
      <div class="column:4 padding:1">
        <div class="fill:grey-l2">
          &nbsp;
        </div>
      </div>
      <div class="column:4 padding:1">
        <div class="fill:grey-l2">
          &nbsp;
        </div>
      </div>
      <div class="column:4 padding:1">
        <div class="fill:grey-l2">
          &nbsp;
        </div>
      </div>
    </div>
  </div>
  <div class="column margin-bottom:2" style="width: 20%;">
    <div class="display:flex flex-wrap height:20 fill:grey-l4 align-content:left">
      <div class="column:4 padding:1">
        <div class="fill:grey-l2">
          &nbsp;
        </div>
      </div>
      <div class="column:4 padding:1">
        <div class="fill:grey-l2">
          &nbsp;
        </div>
      </div>
    </div>
  </div>
  <div class="column margin-bottom:2" style="width: 20%;">
    <div class="display:flex flex-wrap height:20 fill:grey-l4 align-content:center">
      <div class="column:4 padding:1">
        <div class="fill:grey-l2">
          &nbsp;
        </div>
      </div>
      <div class="column:4 padding:1">
        <div class="fill:grey-l2">
          &nbsp;
        </div>
      </div>
    </div>
  </div>
  <div class="column margin-bottom:2" style="width: 20%;">
    <div class="display:flex flex-wrap height:20 fill:grey-l4 align-content:right">
      <div class="column:4 padding:1">
        <div class="fill:grey-l2">
          &nbsp;
        </div>
      </div>
      <div class="column:4 padding:1">
        <div class="fill:grey-l2">
          &nbsp;
        </div>
      </div>
    </div>
  </div>
  <div class="column margin-bottom:2" style="width: 20%;">
    <div class="display:flex flex-wrap height:20 fill:grey-l4 align-content-x:between">
      <div class="column:4 padding:1">
        <div class="fill:grey-l2">
          &nbsp;
        </div>
      </div>
      <div class="column:4 padding:1">
        <div class="fill:grey-l2">
          &nbsp;
        </div>
      </div>
    </div>
  </div>
  <div class="column margin-bottom:2" style="width: 20%;">
    <div class="display:flex flex-wrap height:20 fill:grey-l4 align-content-x:around">
      <div class="column:4 padding:1">
        <div class="fill:grey-l2">
          &nbsp;
        </div>
      </div>
      <div class="column:4 padding:1">
        <div class="fill:grey-l2">
          &nbsp;
        </div>
      </div>
    </div>
  </div>
</div>


{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="align-content:top">
  ...
</div>
<div class="align-content:middle">
  ...
</div>
<div class="align-content:bottom">
  ...
</div>
<div class="align-content-y:between">
  ...
</div>
<div class="align-content-y:around">
  ...
</div>
<div class="align-content:left">
  ...
</div>
<div class="align-content:center">
  ...
</div>
<div class="align-content:right">
  ...
</div>
<div class="align-content-x:between">
  ...
</div>
<div class="align-content-x:around">
  ...
</div>

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
      <code>:top</code> <code>:middle</code> <code>:bottom</code>
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
    </td>
    <td data-label="Attributes">
      <code>:left</code> <code>:center</code> <code>:right</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td class="row:reverse">
      Justify flexible content
    </td>
  </tr>
  <tr>
    <td data-label="Properties">
      <code>align-content-x</code>
    </td>
    <td data-label="Attributes">
      <code>:between</code> <code>:around</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td class="row:reverse">
      Set content distribution
    </td>
  </tr>
  <tr>
    <td data-label="Properties">
      <code>align-content-y</code>
    </td>
    <td data-label="Attributes">
      <code>:between</code> <code>:around</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td class="row:reverse">
      Set content distribution
    </td>
  </tr>
  <tr>
    <td data-label="Properties">
      <code>align-items</code><span class="color:orange">&#42;</span>
    </td>
    <td data-label="Attributes">
      <code>:top</code> <code>:middle</code> <code>:bottom</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td class="row:reverse">
      Set alignement of flexible items
    </td>
  </tr>
  <tr>
    <td data-label="Properties">
      <code>align-self</code><span class="color:orange">&#42;</span>
    </td>
    <td data-label="Attributes">
      <code>:top</code> <code>:middle</code> <code>:bottom</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td class="row:reverse">
      Set independent alignment
    </td>
  </tr>
</table>
<p class="margin-top:0 font-size:tiny color:orange">
  &#42; These properties have a default values set when used without modifiers.
</p>
