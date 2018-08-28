+++
title = "Slidemenu"
date = "2018-04-11T09:16:45+12:00"
family = "Module"
draft = false
description = "Slide panel navigation for mobile."
+++

### Basic Usage

Defined with `slidemenu` and initialized with javascript. Slidemenu is a fixed element and must belong outside of all containers.

```html
<aside class="slidemenu">
  <div class="slidemenu/overlay">

  </div>
  <div class="slidemenu/content">
    <div class="slidemenu/close">

    </div>
    ...
  </div>
</aside>
```

```javascript
  var slidemenu = new Slidemenu();
```

### Slide Direction

You can change the direction of the slide with the `slide-direction` property.

```html
<aside class="slidemenu slide-direction:right">
  <div class="slidemenu/overlay">

  </div>
  <div class="slidemenu/content">
    ...
  </div>
</aside>
```

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
        <code>.slidemenu</code>
      </td>
      <td data-label="Description">
        Define the element class name to initialize.
      </td>
    </tr>
    <tr>
      <td data-label="Setting">
        <code>toggleClass</code>
      </td>
      <td data-label="Default">
        <code>.js-hamburger</code>
      </td>
      <td data-label="Description">
        Define the element class name to toggle
      </td>
    </tr>
    <tr>
      <td data-label="Setting">
        <code>closeClass</code>
      </td>
      <td data-label="Default">
        <code>.slidemenu/close</code>
      </td>
      <td data-label="Description">
        Define the element class name to close
      </td>
    </tr>
  </tbody>
</table>
