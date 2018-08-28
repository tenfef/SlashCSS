+++
title = "Menu"
date = "2018-04-11T09:16:45+12:00"
family = "Module"
draft = false
description = "The nav component provides you with a standard responsive navigation bar."
+++

### Basic Navigation

The `menu` component is built using flex and is useful for building menu bars.

<div class="fill:blue padding:u4 margin-bottom:u2">
  <nav class="menu" role="menu">
    <div class="menu/content">
      <a href="#" class="menu/item is-active">
        A
      </a>
      <a href="#" class="menu/item">
        B
      </a>
      <a href="#" class="menu/item">
        C
      </a>
    </div>
    <div class="menu/content">
      <a href="#" class="menu/item">
        D
      </a>
      <a href="#" class="menu/item">
        E
      </a>
    </div>
  </nav>
</div>

```html
<nav class="menu" role="menu">
  <div class="menu/content">
    <a href="#" class="menu/item is-active">
      A
    </a>
    <a href="#" class="menu/item">
      B
    </a>
    <a href="#" class="menu/item">
      C
    </a>
  </div>
  <div class="menu/content">
    <a href="#" class="menu/item">
      D
    </a>
    <a href="#" class="menu/item">
      E
    </a>
  </div>
</nav>
```

### Local Variables

You can override this component using the following local variables.

```css
:root {
  --menu-height: var(--u10);
  --menu-border: var(--border);
  --menu-color: var(--grey-d2);
  --menu-mobile-radius: var(--radius);
  --menu-mobile-shadow: 0px 5px 5px 0px rgba(0,60,200,0.1);
  --menu-item-padding-x: var(--u6);
  --menu-item-padding-y: var(--u4);
  --menu-item-hover-fill: var(--grey-l5);
  --menu-item-active-fill: var(--grey-l5);
}

```
