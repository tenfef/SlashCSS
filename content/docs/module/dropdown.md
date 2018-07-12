+++
title = "Dropdown DONE"
date = "2018-04-11T09:16:45+12:00"
draft = false
description = "A dropdown menu is a toggleable menu that allows the user to choose one value from a predefined content."
+++

##### Basic Usage

The dropdown component is defined with the `dropdown` class and is initialized with javascript. You can enable hover toggle with the `:hover` modifier.

<div class="dropdown dropdown:hover margin-bottom:2">
  <div class="dropdown/toggle" title="Menu">
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

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="dropdown">
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

{{% codeblock key="initializing" definition="javascript" margin="top" %}}
```javascript
var dropdown = new Dropdown();
```
{{% /codeblock %}}

{{% /codeblock %}}

##### Direction & Alignment

By default the dropdown menu is aligned to the bottom left of its parent container. To override direction and alignment assign the following modifiers:


<div>
  <div class="dropdown dropdown-direction:center margin-bottom:2 js-dropdown">
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
  <div class="dropdown dropdown-direction:left margin-bottom:2 js-dropdown">
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
  <div class="dropdown dropdown-direction:top-left margin-bottom:2 js-dropdown">
    <a class="dropdown/toggle" title="Menu">
      <span class="button button-style:outline button-grow:1">Top Left Menu</span>
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
  <div class="dropdown dropdown-direction:top-center margin-bottom:2 js-dropdown">
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

{{% codeblock key="initializing" definition="html" margin="bottom" %}}
```html
<div class="dropdown dropdown-direction:center">
  <a class="dropdown/toggle">
    ...
  </a>
  <div class="dropdown/content">
    ...
  </div>
</div>

<div class="dropdown dropdown-direction:left">
  <a class="dropdown/toggle">
    ...
  </a>
  <div class="dropdown/content">
    ...
  </div>
</div>

<div class="dropdown dropdown-direction:top-left">
  <a class="dropdown/toggle">
    ...
  </a>
  <ul class="dropdown/content">
    ...
  </ul>
</div>

<div class="dropdown dropdown-direction:top-center">
  <a class="dropdown/toggle">
    ...
  </a>
  <ul class="dropdown/content">
    ...
  </ul>
</div>
```
{{% /codeblock %}}

##### Local Variables

You can override styling using the following local variables.

{{% codeblock key="language" definition="css" margin="bottom" %}}
```css
:root {
  --dropdown-body-fill: var(--white);
  --dropdown-body-radius: var(--radius);
  --dropdown-body-shadow: 0px 0px 0px 1px var(--border-color);

  --dropdown-item-padding: var(--u1) var(--u1);
  --dropdown-item-color: var(--grey-dark-1);
  --dropdown-item-hover-color: var(--grey-dark-2);
  --dropdown-item-hover-fill: var(--grey-light-5);
  --dropdown-item-active-fill: var(--grey-light-4);
}
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
      <code>dropdown</code>
    </td>
    <td data-label="Attributes">
      <code>:hover</code>
    </td>
    <td data-label="Responsive">
      No
    </td>
    <td class="row:reverse">
      Enable hover dropdowns
    </td>
  </tr>
  <tr>
    <td data-label="Properties">
      <code>dropdown-direction</code>
    </td>
    <td data-label="Attributes">
      <code>:center</code> <code>:left</code> <code>:top</code>
      <code>:top-center</code> <code>:top-left</code>
    </td>
    <td data-label="Responsive">
      No
    </td>
    <td class="row:reverse">
      Define dropdown position and fade in direction
    </td>
  </tr>
</table>

##### JS Settings

<table class="table width:100% ">
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
