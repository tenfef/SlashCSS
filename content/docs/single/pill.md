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

{{% codeblock key="language" definition="html" margin="top" %}}
```html
<div class="pill">Pill</div>
```
{{% /codeblock %}}

### Pill Groups

Pills can be joined to form a multi-pill pill with the `pills` component.

<div class="pills">
  <div class="pill">Colors</div>
  <div class="pill fill:grey-l3 color:black">YES</div>
</div>

{{% codeblock key="language" definition="html" margin="top" %}}
```html
<div class="pills">
  <div class="pill">Colors</div>
  <div class="pill fill:grey-l3 color:black">YES</div>
</div>
```
{{% /codeblock %}}

### Colorful Pills

You can change the background color of your pills with the `fill` component.

<div class="pill fill:red">Button</div>
<div class="pill fill:pink">Button</div>
<div class="pill fill:violet">Button</div>
<div class="pill fill:purple">Button</div>
<div class="pill fill:navy">Button</div>
<div class="pill fill:blue">Button</div>
<div class="pill fill:teal">Button</div>
<div class="pill fill:green">Button</div>
<div class="pill fill:lime">Button</div>
<div class="pill fill:yellow">Button</div>
<div class="pill fill:orange">Button</div>
<div class="pill fill:brown">Button</div>
<div class="pill fill:grey">Button</div>
<div class="pill fill:grey-l4 color:black">Button</div>
<div class="pill fill:black">Button</div>

{{% codeblock key="language" definition="html" margin="top" %}}
```html
<div class="pill fill:red">Button</div>
<div class="pill fill:pink">Button</div>
<div class="pill fill:violet">Button</div>
<div class="pill fill:purple">Button</div>
<div class="pill fill:navy">Button</div>
<div class="pill fill:blue">Button</div>
<div class="pill fill:teal">Button</div>
<div class="pill fill:green">Button</div>
<div class="pill fill:lime">Button</div>
<div class="pill fill:yellow">Button</div>
<div class="pill fill:orange">Button</div>
<div class="pill fill:brown">Button</div>
<div class="pill fill:grey">Button</div>
<div class="pill fill:grey-l4 color:black">Button</div>
<div class="pill fill:black">Button</div>
```
{{% /codeblock %}}

### Local Variables

You can override styling using the following local variables.

{{% codeblock key="language" definition="css" margin="bottom" %}}
```css
:root {
  --pill-radius: 3px;
}
```
{{% /codeblock %}}
