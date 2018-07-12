+++
title = "Row DONE"
date = "2018-04-11T09:16:45+12:00"
draft = false
description = "The basics of using the column component to horizontally structure layout."
+++

##### Basic Usage

The `row` component works alongside the column component and applies a horizontal sectioning based on the flex system.

<!-- 6 Columns -->
<div class="row margin-bottom:2">
  <div class="column">
    <div class="padding:1 fill:blue">
      &nbsp;
    </div>
  </div>
  <div class="column">
    <div class="padding:1 fill:blue-light-2">
      &nbsp;
    </div>
  </div>
  <div class="column">
    <div class="padding:1 fill:blue">
      &nbsp;
    </div>
  </div>
</div>

<!-- 6 Columns -->
<div class="row margin-bottom:2">
  <div class="column">
    <div class="padding:1 fill:blue-light-2">
      &nbsp;
    </div>
  </div>
  <div class="column">
    <div class="padding:1 fill:blue">
      &nbsp;
    </div>
  </div>
</div>


{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="row">
  <div class="column">
    ...
  </div>
  <div class="column">
    ...
  </div>
  <div class="column">
    ...
  </div>
</div>

<div class="row">
  <div class="column">
    ...
  </div>
  <div class="column">
    ...
  </div>
</div>

...
```
{{% /codeblock %}}

##### Row Gutters

You can apply gutter to your columns with the `row-gutter` property. Standard media query suffixes can be applied.

<div class="row row-gutter:1 margin-bottom:2">
  <div class="column">
    <div class="padding:1 fill:blue-light-2">
      &nbsp;
    </div>
  </div>
  <div class="column">
    <div class="padding:1 fill:blue">
      &nbsp;
    </div>
  </div>
  <div class="column">
    <div class="padding:1 fill:blue-light-2">
      &nbsp;
    </div>
  </div>
  <div class="column">
    <div class="padding:1 fill:blue">
      &nbsp;
    </div>
  </div>
</div>

<div class="row row-gutter:5 margin-bottom:2">
  <div class="column">
    <div class="padding:1 fill:blue-light-2">
      &nbsp;
    </div>
  </div>
  <div class="column">
    <div class="padding:1 fill:blue">
      &nbsp;
    </div>
  </div>
  <div class="column">
    <div class="padding:1 fill:blue-light-2">
      &nbsp;
    </div>
  </div>
  <div class="column">
    <div class="padding:1 fill:blue">
      &nbsp;
    </div>
  </div>
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="row row-gutter:1">
  ...
</div>
<div class="row row-gutter:2">
  ...
</div>
<div class="row row-gutter:3">
  ...
</div>
<div class="row row-gutter:4">
  ...
</div>
<div class="row row-gutter:5">
  ...
</div>
```
{{% /codeblock %}}

##### Row Media

The row can also act as a media object component with the `:media` modifier.

<div class="row:media row-gutter:1 align-item:middle margin-bottom:2">
  <div class="column">
    <img src="https://pbs.twimg.com/profile_images/803356024690216960/CH3i813s_400x400.jpg" class="image image-shape:round image-size:5 fill:primary">
  </div>
  <div class="column">
    <div>
      <p class="font font-weight:medium color:black font-height:0">Jin Park</p>
      <span class="font-size:tiny font-height:0">@zapcss</span>
    </div>
  </div>
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="row:media">
  <div class="column">
    Image Left
  </div>
  <div class="column display:flex align-item:middle">
    Text Right
  </div>
</div>
```
{{% /codeblock %}}

##### Local Variables

You can override styling using the following local variables.

{{% codeblock key="language" definition="css" margin="bottom" %}}
```css
$row-gutters: 5 !default;
```
{{% /codeblock %}}

##### Options

The following modifiers are available.

<table class="table width:100% table:pile">
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
      <code>row</code>
    </td>
    <td data-label="Attributes">
      <code>:media</code>
    </td>
    <td data-label="Responsive">
      No
    </td>
    <td class="row:reverse">
      Media object layout
    </td>
  </tr>

  <tr>
    <td data-label="Properties">
      <code>row-gutter</code>
    </td>
    <td data-label="Attributes">
      <code>:1</code> ... <code>:5</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td class="row:reverse">
      Set gutter widths
    </td>
  </tr>
</table>
