+++
title = "Table"
date = "2018-04-11T09:16:45+12:00"
draft = false
description = "The table module is useful for displaying grid based data and content."
+++

##### Basic Usage

The table module is defined with the `table` class. By default the table width will only be as wide to fit the content. To make the table span the full width assign the `width:fluid` modifier. Table rows or table cells can have hover states using the `hover` component.

<table class="table width:fluid margin-bottom:2">
  <thead>
    <tr>
      <th>Head</th>
      <th>Head</th>
      <th>Head</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td class="hover-fill:background-focus">Cell</td>
      <td class="hover hover-color:red">Cell</td>
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


{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<table class="table width:fluid margin-bottom:2">
  <thead>
    <tr>
      <th>Head</th>
      <th>Head</th>
      <th>Head</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td class="hover-fill:background-focus">Cell</td>
      <td class="hover hover-color:red">Cell</td>
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
{{% /codeblock %}}

##### Responsive Tables

Tables can be responsive with the `table:pile` modifier. Header labels can be applied by adding the attribute `data-label` to the `<td>` cell.

<table class="table width:fluid elevate table:pile margin-bottom:2">
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

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<table class="table width:fluid elevate table:pile margin-bottom:2">
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
{{% /codeblock %}}

##### Local Root Variables

You can override styling using the following local root variables.

{{% codeblock key="language" definition="css" margin="bottom" %}}
```css
:root {
  --table-border: var(--border);
}
```
{{% /codeblock %}}

##### Settings

The following settings are available.

<table class="table width:fluid table:pile">
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
      <code>:pile</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td class="row:reverse">
      Enable responsiveness
    </td>
  </tr>
</table>
