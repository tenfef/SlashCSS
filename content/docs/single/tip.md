+++
title = "Tip"
date = "2018-04-11T09:16:45+12:00"
draft = false
description = "The tip component adds tooltip functionality to any given element using pseudo elements."
+++

##### Basic Usage

The tip component is defined by adding a data attribute `tip` with content.

<button class="button button-style:outline button-grow:1 tip" tip="Just a simple tooltip">
  Basic Tooltip
</button>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<button class="button button-style:outline button-grow:1 tip" tip="Just a simple tooltip">
  Basic Tooltip
</button>
```
{{% /codeblock %}}

##### Tooltip Positioning

Tooltips can be positioned by defining its position with the data attribute `tip-position`.

<button class="button button-style:outline button-grow:1 tip" tip="Just a simple tooltip">
  Top Tooltip
</button>

<button class="button button-style:outline button-grow:1 tip tip-position:left" tip="Just a simple tooltip">
  Left Tooltip
</button>

<button class="button button-style:outline button-grow:1 tip tip-position:right" tip="Just a simple tooltip">
  Right Tooltip
</button>

<button class="button button-style:outline button-grow:1 tip tip-position:bottom" tip="Just a simple tooltip">
  Bottom Tooltip
</button>



{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<button class="tip" tip="Just a simple tooltip">
  Top Tooltip
</button>

<button class="tip tip-position:left" tip="Just a simple tooltip">
  Left Tooltip
</button>

<button class="tip tip-position:right" tip="Just a simple tooltip">
  Right Tooltip
</button>

<button class="tip tip-position:bottom" tip="Just a simple tooltip">
  Bottom Tooltip
</button>
```
{{% /codeblock %}}

##### Local Variables

You can override styling using the following local variables.

{{% codeblock key="language" definition="css" margin="bottom" %}}
```css
:root {
  --tip-fill: var(--grey);
}
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
      <code>tip-position</code>
    </td>
    <td data-label="Attributes">
      <code>:right</code> <code>:bottom</code> <code>:left</code>
    </td>
    <td data-label="Responsive">
      No
    </td>
    <td class="row:reverse">
      Set position of tip
    </td>
  </tr>
</table>
