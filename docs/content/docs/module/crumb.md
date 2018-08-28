+++
title = "Crumb"
date = "2018-04-11T09:16:45+12:00"
family = "Module"
draft = false
description = "The crumb component provides visual information of the current page location in context to the overall parent hierarchy."
+++

### Basic Usage

<div class="crumb margin-bottom:u2">
  <a href="#" class="crumb/item">Breadcrumb</a>
  <span class="crumb/trail">/</span>
  <a href="#" class="crumb/item">Breadcrumb</a>
  <span class="crumb/trail">/</span>
  <span class="crumb/item is-active">Current Page</span>
</div>

```html
<div class="crumb">
  <a href="#" class="crumb/item">Breadcrumb</a>
  <span class="crumb/trail">/</span>
  <a href="#" class="crumb/item">Breadcrumb</a>
  <span class="crumb/trail">/</span>
  <span class="crumb/item is-active">Current Page</span>
</div>
```

### Local Root Variables

You can override styling using the following local root variables.

```css
:root {
  --crumb-link-color: var(--navy);
  --crumb-active-color: var(--default-color);
  --crumb-trail-color: var(--grey-l3);
  --crumb-trail-gap: 1rem;
}
```
