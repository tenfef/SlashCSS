+++
title = "Menu"
date = "2018-04-11T09:16:45+12:00"
draft = false
description = "The nav component provides you with a standard responsive navigation bar."
+++

##### Basic Navigation

The `menu` component is built using flex and is useful for building menu bars.

<div class="fill:blue padding:2 margin-bottom:2">
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

{{% codeblock key="language" definition="html" margin="bottom" %}}
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
{{% /codeblock %}}

##### Local Variables

You can override styling using the following local variables.

{{% codeblock key="language" definition="css" margin="bottom" %}}
```css
:root {
  --menu-height: var(--u6);
  --menu-border: var(--border);
  --menu-color: var(--grey-d2);
  --menu-mobile-radius: var(--radius);
  --menu-mobile-shadow: 0px 5px 5px 0px rgba(0,60,200,0.1);;
  --menu-item-hover-fill: var(--grey-l5);
  --menu-item-active-fill: var(--grey-l4);
}
```
{{% /codeblock %}}
