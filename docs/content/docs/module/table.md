+++
title = "Table"
date = "2018-04-11T09:16:45+12:00"
family = "Module"
draft = false
description = "The table module is useful for displaying grid based data and content."
+++

### Basic Usage

The table component is defined with the `table` class. By default the table width will only be as wide to fit the content. To make the table span the full width assign the `width:100%` component. Table rows or table cells can have hover states using the `hover` component.

<table class="table width:100% margin-bottom:u2">
  <thead>
    <tr>
      <th>Head</th>
      <th>Head</th>
      <th>Head</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td class="hover hover-fill:grey-l4 hover-color:grey-d2">Hover me</td>
      <td class="hover hover hover-color:red">Hover me</td>
      <td>Cell</td>
    </tr>
    <tr>
      <td>Cell</td>
      <td>Cell</td>
      <td>Cell</td>
    </tr>
    <tr>
      <td>Cell</td>
      <td>Cell</td>
      <td>Cell</td>
    </tr>
  </tbody>
</table>


```html
<table class="table width:100%">
  <thead>
    <tr>
      <th>Head</th>
      <th>Head</th>
      <th>Head</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td class="hover hover-fill:grey-l4 hover-color:grey-d2">Hover me</td>
      <td class="hover hover hover-color:red">Hover me</td>
      <td>Cell</td>
    </tr>
    <tr>
      <td>Cell</td>
      <td>Cell</td>
      <td>Cell</td>
    </tr>
    <tr>
      <td>Cell</td>
      <td>Cell</td>
      <td>Cell</td>
    </tr>
  </tbody>
</table>
```

### Responsive Tables

Tables can be responsive with the `table:pile` modifier. Header labels can be applied by adding the attribute `data-label` to the `<td>` cell. Additionally, you can apply the `elevate` component to change the style of your table.

<table class="table width:100% elevate table:pile table@sm:unpile margin-bottom:u2">
  <thead>
    <tr>
      <th>Head 1</th>
      <th>Head 2</th>
      <th>Head 3</th>
      <th>Head 4</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td data-label="Label 1">Cell</td>
      <td data-label="Label 2">Cell</td>
      <td data-label="Label 3">Cell</td>
      <td data-label="Label 4">Cell</td>
    </tr>
    <tr>
      <td data-label="Label 1">Cell</td>
      <td data-label="Label 2">Cell</td>
      <td data-label="Label 3">Cell</td>
      <td data-label="Label 4">Cell</td>
    </tr>
  </tbody>
</table>

```html
<table class="table width:100% elevate table:pile table@sm:unpile">
  <thead>
    <tr>
      <th>Head 1</th>
      <th>Head 2</th>
      <th>Head 3</th>
      <th>Head 4</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td data-label="Label 1">Cell</td>
      <td data-label="Label 2">Cell</td>
      <td data-label="Label 3">Cell</td>
      <td data-label="Label 4">Cell</td>
    </tr>
    <tr>
      <td data-label="Label 1">Cell</td>
      <td data-label="Label 2">Cell</td>
      <td data-label="Label 3">Cell</td>
      <td data-label="Label 4">Cell</td>
    </tr>
  </tbody>
</table>
```

### Local Root Variables

You can override styling using the following local root variables.

```css
:root {
  --table-border: var(--border);
}
```

### Settings

The following settings are available.

<table class="table width:100%">
  <thead>
    <tr>
      <th>
        Properties
      </th>
      <th>
        Attributes
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
      <code>table</code>
    </td>
    <td data-label="Attributes">
      <code>:pile</code> <code>:unpile</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td>
      Enable/disable responsiveness
    </td>
  </tr>
</table>
