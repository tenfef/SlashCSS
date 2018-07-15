+++
title = "Align"
date = "2018-04-11T09:16:45+12:00"
draft = false
description = "The align component sets the alignment of content in various ways."
+++

##### Text Alignment

The basic `align` property controls text alignment and vertical alignment.

<div class="margin-bottom:2">
  <h6 class="align:left">Left Aligned</h6>
  <h6 class="align:center">Center Aligned</h6>
  <h6 class="align:right">Right Aligned</h6>
</div>

<div class="font-size:h1 fill:grey-light-4 color:white margin-bottom:2 padding:2">
  <span class="image image-size:2 display:inline-block fill:blue color:white align:top"></span>
 <span class="image image-size:2 display:inline-block fill:blue color:white align:middle"></span>
 <span class="image image-size:2 display:inline-block fill:blue color:white align:bottom"></span>
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<h6 class="align:left">Left Aligned</h6>
<h6 class="align:center">Center Aligned</h6>
<h6 class="align:right">Right Aligned</h6>

<span class="align:top"></span>
<span class="align:middle"></span>
<span class="align:bottom"></span>
```
{{% /codeblock %}}

##### Responsive Alignments

Responsive suffixes can be applied to all alignment properties.

<div class="margin-bottom:2">
  <h6 class="align:left">Left</h6>
  <h6 class="align@md:center">Center Medium</h6>
  <h6 class="align@lg:right">Large Right</h6>
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<h6 class="align:left">Left</h6>
<h6 class="align@md:center">Center Medium</h6>
<h6 class="align@lg:right">Large Right</h6>
```
{{% /codeblock %}}

##### Item Alignment

The `align-items` property specifies the default alignment for items inside the flexible container.

<div class="row">
  <div class="column fill:grey-light-4">
    <div class="height:10 display:flex align-items:top">
      <div class="image-size:5 fill:grey-dark-1 color:white display:flex align-item:middle align-content:center"></div>
    </div>
  </div>
</div>

##### Content Alignment

The `align-content` property modifies the behavior of the flex-wrap property. It is similar to align-items, but instead of aligning flex items, it aligns flex lines.

<div class="row">
  <div class="column">
    <div class="float:left display:flex flex-wrap width:20% height:30 fill:grey-light-4">
      <div class="image-size:5 fill:grey-dark-1 color:white display:flex align-item:middle align-content:center">1</div>
      <div class="image-size:5 fill:grey-dark-1 color:white display:flex align-item:middle align-content:center">2</div>
      <div class="image-size:5 fill:grey-dark-1 color:white display:flex align-item:middle align-content:center">3</div>
      <div class="image-size:5 fill:grey-dark-1 color:white display:flex align-item:middle align-content:center">4</div>
      <div class="image-size:5 fill:grey-dark-1 color:white display:flex align-item:middle align-content:center">5</div>
      <div class="image-size:5 fill:grey-dark-1 color:white display:flex align-item:middle align-content:center">6</div>
    </div>
    <div class="float:left display:flex flex-wrap width:20% height:30 align-content:middle fill:grey-light-4">
      <div class="image-size:5 fill:grey-dark-1 color:white display:flex align-item:middle align-content:center flex-item">1</div>
      <div class="image-size:5 fill:grey-dark-1 color:white display:flex align-item:middle align-content:center flex-item">2</div>
      <div class="image-size:5 fill:grey-dark-1 color:white display:flex align-item:middle align-content:center flex-item">3</div>
      <div class="image-size:5 fill:grey-dark-1 color:white display:flex align-item:middle align-content:center flex-item">4</div>
      <div class="image-size:5 fill:grey-dark-1 color:white display:flex align-item:middle align-content:center flex-item">5</div>
      <div class="image-size:5 fill:grey-dark-1 color:white display:flex align-item:middle align-content:center flex-item">6</div>
    </div>
    <div class="float:left display:flex flex-wrap width:20% height:30 align-content:bottom fill:grey-light-4">
      <div class="image-size:5 fill:grey-dark-1 color:white display:flex align-item:middle align-content:center flex-item">1</div>
      <div class="image-size:5 fill:grey-dark-1 color:white display:flex align-item:middle align-content:center flex-item">2</div>
      <div class="image-size:5 fill:grey-dark-1 color:white display:flex align-item:middle align-content:center flex-item">3</div>
      <div class="image-size:5 fill:grey-dark-1 color:white display:flex align-item:middle align-content:center flex-item">4</div>
      <div class="image-size:5 fill:grey-dark-1 color:white display:flex align-item:middle align-content:center flex-item">5</div>
      <div class="image-size:5 fill:grey-dark-1 color:white display:flex align-item:middle align-content:center flex-item">6</div>
    </div>
    <div class="float:left display:flex flex-wrap width:20% height:30 align-content-y:between fill:grey-light-4">
      <div class="image-size:5 fill:grey-dark-1 color:white display:flex align-item:middle align-content:center flex-item">1</div>
      <div class="image-size:5 fill:grey-dark-1 color:white display:flex align-item:middle align-content:center flex-item">2</div>
      <div class="image-size:5 fill:grey-dark-1 color:white display:flex align-item:middle align-content:center flex-item">3</div>
      <div class="image-size:5 fill:grey-dark-1 color:white display:flex align-item:middle align-content:center flex-item">4</div>
      <div class="image-size:5 fill:grey-dark-1 color:white display:flex align-item:middle align-content:center flex-item">5</div>
      <div class="image-size:5 fill:grey-dark-1 color:white display:flex align-item:middle align-content:center flex-item">6</div>
    </div>
    <div class="float:left display:flex flex-wrap width:20% height:30 align-content-y:around fill:grey-light-4">
      <div class="image-size:5 fill:grey-dark-1 color:white display:flex align-item:middle align-content:center flex-item">1</div>
      <div class="image-size:5 fill:grey-dark-1 color:white display:flex align-item:middle align-content:center flex-item">2</div>
      <div class="image-size:5 fill:grey-dark-1 color:white display:flex align-item:middle align-content:center flex-item">3</div>
      <div class="image-size:5 fill:grey-dark-1 color:white display:flex align-item:middle align-content:center flex-item">4</div>
      <div class="image-size:5 fill:grey-dark-1 color:white display:flex align-item:middle align-content:center flex-item">5</div>
      <div class="image-size:5 fill:grey-dark-1 color:white display:flex align-item:middle align-content:center flex-item">6</div>
    </div>
    <div class="float:left display:flex flex-wrap width:20% height:30 align-content-y:even fill:grey-light-4">
      <div class="image-size:5 fill:grey-dark-1 color:white display:flex align-item:middle align-content:center flex-item">1</div>
      <div class="image-size:5 fill:grey-dark-1 color:white display:flex align-item:middle align-content:center flex-item">2</div>
      <div class="image-size:5 fill:grey-dark-1 color:white display:flex align-item:middle align-content:center flex-item">3</div>
      <div class="image-size:5 fill:grey-dark-1 color:white display:flex align-item:middle align-content:center flex-item">4</div>
      <div class="image-size:5 fill:grey-dark-1 color:white display:flex align-item:middle align-content:center flex-item">5</div>
      <div class="image-size:5 fill:grey-dark-1 color:white display:flex align-item:middle align-content:center flex-item">6</div>
    </div>
  </div>
</div>

##### Content Alignment

The `align-content` property modifies the behavior of the flex-wrap property. It is similar to align-items, but instead of aligning flex items, it aligns flex lines.

<div class="float:left width:10% height:30 flex-start">
  <div class="image-size:5 fill:black flex-item">1</div>
  <div class="image-size:5 fill:black flex-item">2</div>
  <div class="image-size:5 fill:black flex-item">3</div>
  <div class="image-size:5 fill:black flex-item">4</div>
  <div class="image-size:5 fill:black flex-item">5</div>
  <div class="image-size:5 fill:black flex-item">6</div>
</div>

<div class="float:left width:10% height:30 flex-end">
  <div class="image-size:5 fill:black flex-item">1</div>
  <div class="image-size:5 fill:black flex-item">2</div>
  <div class="image-size:5 fill:black flex-item">3</div>
  <div class="image-size:5 fill:black flex-item">4</div>
  <div class="image-size:5 fill:black flex-item">5</div>
  <div class="image-size:5 fill:black flex-item">6</div>
</div>

<div class="float:left width:10% height:30 center">
  <div class="image-size:5 fill:black flex-item">1</div>
  <div class="image-size:5 fill:black flex-item">2</div>
  <div class="image-size:5 fill:black flex-item">3</div>
  <div class="image-size:5 fill:black flex-item">4</div>
  <div class="image-size:5 fill:black flex-item">5</div>
  <div class="image-size:5 fill:black flex-item">6</div>
</div>
