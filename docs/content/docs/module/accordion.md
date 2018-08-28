+++
title = "Accordion"
date = "2018-04-11T09:16:45+12:00"
family = "Module"
draft = false
description = "Accordions are useful when you want to hide and show large content."
+++

### Basic Usage

Basic accordion markup. To disable rotating arrows, remove the `accordion/arrow` child element. Styling is minimum to allow for easier style overrides.

<div class="accordion margin-bottom:u2">
  <div class="accordion/item">
    <a class="accordion/header">
      Panel 1
      <span class="accordion/arrow"></span>
    </a>
    <div class="accordion/content">
      <div class="accordion/body">
        Pellentesque fermentum dolor. Aliquam quam lectus, facilisis auctor, ultrices ut, elementum vulputate, nunc.
      </div>
    </div>
  </div>
  <div class="accordion/item">
    <a class="accordion/header">
      Panel 2
      <span class="accordion/arrow"></span>
    </a>
    <div class="accordion/content">
      <div class="accordion/body">
        Donec nec justo eget felis facilisis fermentum. Aliquam porttitor mauris sit amet orci. Aenean dignissim pellentesque felis.
      </div>
    </div>
  </div>
  <div class="accordion/item">
    <a class="accordion/header">
      Panel 3
      <span class="accordion/arrow"></span>
    </a>
    <div class="accordion/content">
      <div class="accordion/body">
        Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Phasellus hendrerit. Pellentesque aliquet nibh nec urna. In nisi neque, aliquet vel, dapibus id, mattis vel, nisi. Sed pretium, ligula sollicitudin laoreet viverra, tortor libero sodales leo, eget blandit nunc tortor eu nibh. Nullam mollis. Ut justo. Suspendisse potenti.
      </div>
    </div>
  </div>
</div>

```html
<div class="accordion js-accordion">
  <div class="accordion/item">
    <a class="accordion/header">
      Panel 1
      <span class="accordion/arrow"></span>
    </a>
    <div class="accordion/content">
      ...
    </div>
  </div>
  <div class="accordion/item">
    <a class="accordion/header">
      Panel 2
      <span class="accordion/arrow"></span>
    </a>
    <div class="accordion/content">
      ...
    </div>
  </div>
  <div class="accordion/item">
    <a class="accordion/header">
      Panel 3
      <span class="accordion/arrow"></span>
    </a>
    <div class="accordion/content">
      ...
    </div>
  </div>
</div>
```

```javascript
var accordion = new Accordion();
```

### Local Variables

You can override this component using the following local variables.

```css
:root {
  --accordion-fill: var(--white);
  --accordion-header-padding: var(--u1) var(--u2);
  --accordion-body-padding: var(--u2);
  --accordion-transition: var(--transition);
  --accordion-arrow-fill: var(--black);
}
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
        <code>.accordion</code>
      </td>
      <td data-label="Description">
        Define the element class name to initialize.
      </td>
    </tr>
  </tbody>
</table>
