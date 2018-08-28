+++
title = "Pill"
date = "2018-04-11T09:16:45+12:00"
family = "Single"
draft = false
description = "The pill component are small tag based components useful for highlighting taxonomic data."
+++

### Basic Usage

Defined with `pill`. Pills can also be nested inside `pills`.

<div class="pill">Pill</div>

```html
<div class="pill">Pill</div>
```

### Pill Groups

Pills can be joined to form a multi-pill pill with the `pills` component.

<div class="pills">
  <div class="pill">Colors</div>
  <div class="pill fill:grey-l3 color:black">YES</div>
</div>

```html
<div class="pills">
  <div class="pill">Colors</div>
  <div class="pill fill:grey-l3 color:black">YES</div>
</div>
```

### Colorful Pills

You can change the background color of your pills with the `fill` component.

<div class="pill fill:red">Pill</div>
<div class="pill fill:pink">Pill</div>
<div class="pill fill:violet">Pill</div>
<div class="pill fill:purple">Pill</div>
<div class="pill fill:navy">Pill</div>
<div class="pill fill:blue">Pill</div>
<div class="pill fill:teal">Pill</div>
<div class="pill fill:green">Pill</div>
<div class="pill fill:lime">Pill</div>
<div class="pill fill:yellow">Pill</div>
<div class="pill fill:orange">Pill</div>
<div class="pill fill:brown">Pill</div>
<div class="pill fill:grey">Pill</div>
<div class="pill fill:grey-l4 color:black">Pill</div>
<div class="pill fill:black">Pill</div>

```html
<div class="pill fill:red">Pill</div>
<div class="pill fill:pink">Pill</div>
<div class="pill fill:violet">Pill</div>
<div class="pill fill:purple">Pill</div>
<div class="pill fill:navy">Pill</div>
<div class="pill fill:blue">Pill</div>
<div class="pill fill:teal">Pill</div>
<div class="pill fill:green">Pill</div>
<div class="pill fill:lime">Pill</div>
<div class="pill fill:yellow">Pill</div>
<div class="pill fill:orange">Pill</div>
<div class="pill fill:brown">Pill</div>
<div class="pill fill:grey">Pill</div>
<div class="pill fill:grey-l4 color:black">Pill</div>
<div class="pill fill:black">Pill</div>
```

### Local Variables

You can override this component using the following local variables.

```css
:root {
  --pill-radius: 3px;
}
```
