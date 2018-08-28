+++
title = "Grid"
date = "2018-04-11T09:16:45+12:00"
family = "Layout"
draft = false
description = "The basics of using the grid component to structure layout."
+++

### Basic Usage

Sometimes your grid layout might quite fit in a row or column based structure. The `grid` component provides a way to build evenly distributed content in both directions.

<div class="grid grid:3">
  <div class="grid/item">
    <div class="padding:u4 fill:blue">
      &nbsp;
    </div>
  </div>
  <div class="grid/item">
    <div class="padding:u4 fill:blue-l4">
      &nbsp;
    </div>
  </div>
  <div class="grid/item">
    <div class="padding:u4 fill:blue">
      &nbsp;
    </div>
  </div>
  <div class="grid/item">
    <div class="padding:u4 fill:blue-l4">
      &nbsp;
    </div>
  </div>
  <div class="grid/item">
    <div class="padding:u4 fill:blue">
      &nbsp;
    </div>
  </div>
  <div class="grid/item">
    <div class="padding:u4 fill:blue-l4">
      &nbsp;
    </div>
  </div>
</div>

```html
<div class="grid">
  <div class="grid/item">
    ...
  </div>
  <div class="grid/item">
    ...
  </div>
  <div class="grid/item">
    ...
  </div>
  <div class="grid/item">
    ...
  </div>
  <div class="grid/item">
    ...
  </div>
  <div class="grid/item">
    ...
  </div>
</div>
```

### Grid Gutters

You can apply gutter to your grid layout with the `grid-gutter` property. Standard media query notations can be applied. You can also assign row or column based gutters seperately with the `row` `column` suffixes.

<div class="grid grid:3 grid-gutter:u8 grid-gutter-row@sm:u6">
  <div class="grid/item">
    <div class="padding:u4 fill:blue">
      &nbsp;
    </div>
  </div>
  <div class="grid/item">
    <div class="padding:u4 fill:blue-l4">
      &nbsp;
    </div>
  </div>
  <div class="grid/item">
    <div class="padding:u4 fill:blue">
      &nbsp;
    </div>
  </div>
  <div class="grid/item">
    <div class="padding:u4 fill:blue-l4">
      &nbsp;
    </div>
  </div>
  <div class="grid/item">
    <div class="padding:u4 fill:blue">
      &nbsp;
    </div>
  </div>
  <div class="grid/item">
    <div class="padding:u4 fill:blue-l4">
      &nbsp;
    </div>
  </div>
</div>

```html
<div class="grid grid:3 grid-gutter:u8 grid-gutter-row@sm:u6">
  <div class="grid/item">
    ...
  </div>
  <div class="grid/item">
    ...
  </div>
  <div class="grid/item">
    ...
  </div>
  <div class="grid/item">
    ...
  </div>
  <div class="grid/item">
    ...
  </div>
  <div class="grid/item">
    ...
  </div>
</div>
```

### Local Variables

You can override this component using the following local variables.

{{% codeblock key="language" definition="css" margin="bottom" %}}
```css
$grid-gutters: 5 !default;

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
      <code>grid</code>
    </td>
    <td data-label="Attributes">
      <code>:2</code> <code>:u4</code> <code>:u6</code> <code>:u8</code> <code>:u10</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td class="row:reverse">
      Set grid column template
    </td>
  </tr>

  <tr>
    <td data-label="Properties">
      <code>grid-gutter</code>
    </td>
    <td data-label="Attributes">
      <code>:2</code> <code>:u4</code> <code>:u6</code> <code>:u8</code> <code>:u10</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td class="row:reverse">
      Set gutter widths
    </td>
  </tr>

  <tr>
    <td data-label="Properties">
      <code>grid-gutter-row</code>
    </td>
    <td data-label="Attributes">
      <code>:2</code> <code>:u4</code> <code>:u6</code> <code>:u8</code> <code>:u10</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td class="row:reverse">
      Set gutter heights
    </td>
  </tr>

  <tr>
    <td data-label="Properties">
      <code>grid-gutter-column</code>
    </td>
    <td data-label="Attributes">
      <code>:2</code> <code>:u4</code> <code>:u6</code> <code>:u8</code> <code>:u10</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td class="row:reverse">
      Set gutter widths
    </td>
  </tr>
</table>
