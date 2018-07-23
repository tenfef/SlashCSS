+++
title = "Label"
date = "2018-04-11T09:16:45+12:00"
draft = false
description = "The label component are small tag based components useful for highlighting taxonomic data."
+++

### Basic Usage

Defined with `label`. Labels can also be nested inside `labels`.

<div class="label">Label</div>

{{% codeblock key="language" definition="html" margin="top" %}}
```html
<div class="label">Label</div>
```
{{% /codeblock %}}

### Label Groups

Labels can be joined to form a multi-label pill with the `labels` component.

<div class="labels">
  <div class="label">Colors</div>
  <div class="label fill:grey-l3 color:black">YES</div>
</div>

{{% codeblock key="language" definition="html" margin="top" %}}
```html
<div class="labels">
  <div class="label">Colors</div>
  <div class="label fill:grey-l3 color:black">YES</div>
</div>
```
{{% /codeblock %}}

### Colorful Labels

You can change the background color of your labels with the `fill` component.

<div class="label fill:red">Button</div>
<div class="label fill:pink">Button</div>
<div class="label fill:violet">Button</div>
<div class="label fill:purple">Button</div>
<div class="label fill:navy">Button</div>
<div class="label fill:blue">Button</div>
<div class="label fill:teal">Button</div>
<div class="label fill:green">Button</div>
<div class="label fill:lime">Button</div>
<div class="label fill:yellow">Button</div>
<div class="label fill:orange">Button</div>
<div class="label fill:brown">Button</div>
<div class="label fill:grey">Button</div>
<div class="label fill:grey-l4 color:black">Button</div>
<div class="label fill:black">Button</div>

{{% codeblock key="language" definition="html" margin="top" %}}
```html
<div class="label fill:red">Button</div>
<div class="label fill:pink">Button</div>
<div class="label fill:violet">Button</div>
<div class="label fill:purple">Button</div>
<div class="label fill:navy">Button</div>
<div class="label fill:blue">Button</div>
<div class="label fill:teal">Button</div>
<div class="label fill:green">Button</div>
<div class="label fill:lime">Button</div>
<div class="label fill:yellow">Button</div>
<div class="label fill:orange">Button</div>
<div class="label fill:brown">Button</div>
<div class="label fill:grey">Button</div>
<div class="label fill:grey-l4 color:black">Button</div>
<div class="label fill:black">Button</div>
```
{{% /codeblock %}}

### Local Variables

You can override styling using the following local variables.

{{% codeblock key="language" definition="css" margin="bottom" %}}
```css
:root {
  --label-radius: 3px;
}
```
{{% /codeblock %}}
