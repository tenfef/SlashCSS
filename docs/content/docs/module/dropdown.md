+++
title = "Dropdown"
date = "2018-04-11T09:16:45+12:00"
family = "Module"
draft = false
description = "A dropdown menu is a toggleable menu that allows the user to choose one value from a predefined content."
+++

### Basic Usage

The dropdown component is defined with the `dropdown` class and is initialized with javascript. You can enable hover toggle with the `hover` component.

<div class="dropdown hover margin-bottom:u2">
  <div class="dropdown/toggle">
    <a class="button button-style:outline button-grow:1">Toggle Menu</a>
  </div>
  <div class="dropdown/content">
    <div class="dropdown/body">
      <a class="dropdown/item">
        Menu Item A
      </a>
      <a class="dropdown/item">
        Menu Item B
      </a>
      <a class="dropdown/item">
        Menu Item C
      </a>
      <a class="dropdown/item">
        Menu Item D
      </a>
    </div>
  </div>
</div>

```html
<div class="dropdown hover">
  <a class="dropdown/toggle">
    Toggle Menu
  </a>
  <div class="dropdown/content">
    <div class="dropdown/body">
      <a class="dropdown/item">
        Menu Item A
      </a>
      <a class="dropdown/item">
        Menu Item B
      </a>
      <a class="dropdown/item">
        Menu Item C
      </a>
      <a class="dropdown/item">
        Menu Item D
      </a>
    </div>
  </div>
</div>
```
```javascript
var dropdown = new Dropdown();
```

### Dropdown Position

By default the dropdown menu is aligned to the bottom left of its parent container. To override position and alignment assign the following modifiers:

<div>
  <div class="dropdown dropdown-position:center margin-bottom:u2">
    <a class="dropdown/toggle" title="Menu">
      <span class="button button-style:outline button-grow:1">Center Menu</span>
    </a>
    <div class="dropdown/content elevate">
      <div class="dropdown/body">
        <a class="dropdown/item">
          Menu Item A
        </a>
        <a class="dropdown/item">
          Menu Item B
        </a>
        <a class="dropdown/item">
          Menu Item C
        </a>
        <a class="dropdown/item">
          Menu Item D
        </a>
      </div>
    </div>
  </div>
</div>

<div>
  <div class="dropdown dropdown-position:right margin-bottom:u2">
    <a class="dropdown/toggle" title="Menu">
      <span class="button button-style:outline button-grow:1">Right Menu</span>
    </a>
    <div class="dropdown/content elevate">
      <div class="dropdown/body">
        <a class="dropdown/item">
          Menu Item A
        </a>
        <a class="dropdown/item">
          Menu Item B
        </a>
        <a class="dropdown/item">
          Menu Item C
        </a>
        <a class="dropdown/item">
          Menu Item D
        </a>
      </div>
    </div>
  </div>
</div>

<div>
  <div class="dropdown dropdown-position:top-right margin-bottom:u2">
    <a class="dropdown/toggle" title="Menu">
      <span class="button button-style:outline button-grow:1">Top Right Menu</span>
    </a>
    <div class="dropdown/content elevate">
      <div class="dropdown/body">
        <a class="dropdown/item">
          Menu Item A
        </a>
        <a class="dropdown/item">
          Menu Item B
        </a>
        <a class="dropdown/item">
          Menu Item C
        </a>
        <a class="dropdown/item">
          Menu Item D
        </a>
      </div>
    </div>
  </div>
</div>

<div>
  <div class="dropdown dropdown-position:top-center margin-bottom:u2">
    <a class="dropdown/toggle" title="Menu">
      <span class="button button-style:outline button-grow:1">Top Center Menu</span>
    </a>
    <div class="dropdown/content elevate">
      <div class="dropdown/body">
        <a class="dropdown/item">
          Menu Item A
        </a>
        <a class="dropdown/item">
          Menu Item B
        </a>
        <a class="dropdown/item">
          Menu Item C
        </a>
        <a class="dropdown/item">
          Menu Item D
        </a>
      </div>
    </div>
  </div>
</div>

```html
<div class="dropdown dropdown-position:center">
  <a class="dropdown/toggle">
    ...
  </a>
  <div class="dropdown/content">
    ...
  </div>
</div>

<div class="dropdown dropdown-position:left">
  <a class="dropdown/toggle">
    ...
  </a>
  <div class="dropdown/content">
    ...
  </div>
</div>

<div class="dropdown dropdown-position:top-left">
  <a class="dropdown/toggle">
    ...
  </a>
  <ul class="dropdown/content">
    ...
  </ul>
</div>

<div class="dropdown dropdown-position:top-center">
  <a class="dropdown/toggle">
    ...
  </a>
  <ul class="dropdown/content">
    ...
  </ul>
</div>
```

### Local Variables

You can override this component using the following local variables.

```css
:root {
  --dropdown-body-fill: var(--white);
  --dropdown-body-radius: var(--radius);
  --dropdown-body-shadow: 0px 0px 0px 1px var(--border-color);

  --dropdown-item-padding: .5rem;
  --dropdown-item-color: var(--grey-d1);
  --dropdown-item-hover-color: var(--grey-d2);
  --dropdown-item-hover-fill: var(--grey-l5);
  --dropdown-item-active-fill: var(--grey-l4);
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
      <code>dropdown</code>
    </td>
    <td data-label="Attributes">
      <code>:hover</code>
    </td>
    <td data-label="Responsive">
      No
    </td>
    <td>
      Enable hoverable dropdowns
    </td>
  </tr>
  <tr>
    <td data-label="Properties">
      <code>dropdown-position</code>
    </td>
    <td data-label="Attributes">
      <code class="margin:u0">:center</code><br><code class="margin:u0">:left</code><br><code class="margin:u0">:top</code><br><code class="margin:u0">:top-center</code><br><code class="margin:u0">:top-left</code>
    </td>
    <td data-label="Responsive">
      No
    </td>
    <td>
      Define dropdown position and fade in position
    </td>
  </tr>
</table>

### JS Settings

<table class="table width:100% table:pile table@sm:unpile">
  <thead>
    <tr>
      <th>
        <strong>Setting</strong>
      </th>
      <th>
        <strong>Default</strong>
      </th>
      <th>
        <strong>Description</strong>
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td data-label="Setting">
        <code>element</code>
      </td>
      <td data-label="Default">
        <code>.dropdown</code>
      </td>
      <td data-label="Description">
        Define the element class name to initialize.
      </td>
    </tr>
  </tbody>
</table>
