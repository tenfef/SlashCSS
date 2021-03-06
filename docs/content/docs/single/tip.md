+++
title = "Tip"
date = "2018-04-11T09:16:45+12:00"
family = "Single"
draft = false
description = "The tip component adds tooltip functionality to any given element using pseudo elements."
+++

### Basic Usage

The tip component is defined by adding a data attribute `tip` with content.

<button class="button button-style:outline tip" tip="Just a simple tooltip">
  Basic Tooltip
</button>

```html
<button class="button button-style:outline tip" tip="Just a simple tooltip">
  Basic Tooltip
</button>
```

### Tooltip Positioning

Tooltips can be positioned by defining its position with the data attribute `tip-position`.

<button class="button button-style:outline tip" tip="Just a simple tooltip">
  Top Tooltip
</button>

<button class="button button-style:outline tip tip-position:left" tip="Just a simple tooltip">
  Left Tooltip
</button>

<button class="button button-style:outline tip tip-position:right" tip="Just a simple tooltip">
  Right Tooltip
</button>

<button class="button button-style:outline tip tip-position:bottom" tip="Just a simple tooltip">
  Bottom Tooltip
</button>

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

### Local Variables

You can override this component using the following local variables.

```css
:root {
  --tip-fill: var(--grey);
}
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
      <code>tip-position</code>
    </td>
    <td data-label="Attributes">
      <code>:right</code> <code>:bottom</code> <code>:left</code>
    </td>
    <td data-label="Responsive">
      No
    </td>
    <td>
      Set position of tip
    </td>
  </tr>
</table>
