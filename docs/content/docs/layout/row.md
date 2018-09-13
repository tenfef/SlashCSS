+++
title = "Row"
date = "2018-04-11T09:16:45+12:00"
family = "Layout"
draft = false
description = "The basics of using the column component to horizontally structure layout."
+++

### Basic Usage

The `row` component works alongside the column component and applies a horizontal sectioning based on the flex system.

<!-- 6 Columns -->
<div class="row margin-bottom:u4">
  <div class="column">
    <div class="padding:u2 fill:blue">
      &nbsp;
    </div>
  </div>
  <div class="column">
    <div class="padding:u2 fill:blue-l2">
      &nbsp;
    </div>
  </div>
  <div class="column">
    <div class="padding:u2 fill:blue">
      &nbsp;
    </div>
  </div>
</div>

<!-- 6 Columns -->
<div class="row margin-bottom:u2">
  <div class="column">
    <div class="padding:u2 fill:blue-l2">
      &nbsp;
    </div>
  </div>
  <div class="column">
    <div class="padding:u2 fill:blue">
      &nbsp;
    </div>
  </div>
</div>

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

### Row Gutters

You can apply gutter to your columns with the `row-gutter` property. Standard media query suffixes can be applied.

<div class="row row-gutter:u4 margin-bottom:u4">
  <div class="column">
    <div class="padding:u2 fill:blue-l2">
      &nbsp;
    </div>
  </div>
  <div class="column">
    <div class="padding:u2 fill:blue">
      &nbsp;
    </div>
  </div>
  <div class="column">
    <div class="padding:u2 fill:blue-l2">
      &nbsp;
    </div>
  </div>
  <div class="column">
    <div class="padding:u2 fill:blue">
      &nbsp;
    </div>
  </div>
</div>

<div class="row row-gutter:u8 margin-bottom:u2">
  <div class="column">
    <div class="padding:u2 fill:blue-l2">
      &nbsp;
    </div>
  </div>
  <div class="column">
    <div class="padding:u2 fill:blue">
      &nbsp;
    </div>
  </div>
  <div class="column">
    <div class="padding:u2 fill:blue-l2">
      &nbsp;
    </div>
  </div>
  <div class="column">
    <div class="padding:u2 fill:blue">
      &nbsp;
    </div>
  </div>
</div>

```html
<div class="row row-gutter:u4">
  ...
</div>
<div class="row row-gutter:u8">
  ...
</div>
```

### Local Variables

You can override this component using the following local variables.

```css
$row-gutters: 5 !default;
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
      <code>row</code>
    </td>
    <td data-label="Attributes">

    </td>
    <td data-label="Responsive">
      No
    </td>
    <td>
      Apply clearing row container
    </td>
  </tr>

  <tr>
    <td data-label="Properties">
      <code>row-gutter</code>
    </td>
    <td data-label="Attributes">
      <code>:u2</code> <code>:u4</code> <code>:u6</code> <code>:u8</code> <code>:u10</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td>
      Set gutter widths
    </td>
  </tr>
</table>
