+++
title = "Button"
date = "2018-04-11T09:16:45+12:00"
draft = false
description = "Colorful and juicy button component in all shapes and sizes."
+++
### Basic Button

A standard button

<button class="button">Button</button>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<button class="button">
  Button
</button>
```
{{% /codeblock %}}

### Sizes

Buttons comes in various sizes, use standard size modifiers to transform its size.

<div class="margin-bottom:6">
  <button class="button button-size:xs">Button</button>
  <button class="button button-size:sm">Button</button>
  <button class="button button-size:md">Button</button>
  <button class="button button-size:lg">Button</button>
  <button class="button button-size:xl">Button</button>
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<button class="button button-size:xs">Button</button>
<button class="button button-size:sm">Button</button>
<button class="button button-size:md">Button</button>
<button class="button button-size:lg">Button</button>
<button class="button button-size:xl">Button</button>
```
{{% /codeblock %}}

### Growing Buttons

Buttons can vary in width.

<div class="distribute-y:1 margin-bottom:6">
  <button class="button">Default</button><br>
  <button class="button button-grow:1">Grow 1</button><br>
  <button class="button button-grow:2">Grow 2</button><br>
  <button class="button button-grow:3">Grow 3</button><br>
  <button class="button button-grow:4">Grow 4</button><br>
  <button class="button button-grow:5">Grow 5</button><br>
  <button class="button width:100%">Fluid</button>
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<button class="button">Default</button>
<button class="button button-grow:1">Grow 1</button>
<button class="button button-grow:2">Grow 2</button>
<button class="button button-grow:3">Grow 3</button>
<button class="button button-grow:4">Grow 4</button>
<button class="button button-grow:5">Grow 5</button>
<button class="button width:100%">Fluid</button>
```
{{% /codeblock %}}

### Shapes

You can apply different corners with the `border` component.

<div class="margin-bottom:6">
  <button class="button">Default</button>
  <button class="button border-radius:sharp">Sharp</button>
  <button class="button border-radius:round">Round</button>
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<button class="button">Default</button>
<button class="button border-radius:sharp">Sharp</button>
<button class="button border-radius:round">Round</button>
```
{{% /codeblock %}}

### Icon Buttons

Buttons can contain icons.

<div class="margin-bottom:6">
  <button class="button button-style:outline font-size:body font-transform:none">
    <i class="fas fa-cloud-upload-alt margin-right:3"></i>
    Upload File
  </button>
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<button class="button button-grow:1 button-style:outline font-size:body font-transform:none">
  <div class="button/icon">
    <i class="fas fa-cloud-upload-alt margin-right:1"></i>
  </div>
  Upload File
</button>
```
{{% /codeblock %}}

### Styles

There are 4 different styles of buttons, default, outline and button-style:physicald.

<div class="margin-bottom:6">
  <button class="button button-grow:1 margin-bottom:6">Default</button>
  <button class="button button-grow:1 elevate margin-bottom:6">Elevated</button>
  <button class="button button-grow:1 button-style:outline margin-bottom:6">Outline</button>
  <button class="button button-grow:1 button-style:flat">Flat</button>
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<button class="button button-grow:1">Default</button>
<button class="button button-grow:1 elevate">Elevated</button>
<button class="button button-grow:1 button-style:outline">Outline</button>
<button class="button button-grow:1 button-style:flat">Flat</button>
```
{{% /codeblock %}}

### Button Weights

Buttons can have different font weights with the font component.

<div class="margin-bottom:6">
  <button class="button font-weight:regular">Regular</button>
  <button class="button font-weight:medium">Medium</button>
  <button class="button font-weight:bold">Bold</button>
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<button class="button font-weight:regular">Regular</button>
<button class="button font-weight:medium">Medium</button>
<button class="button font-weight:bold">Bold</button>
```
{{% /codeblock %}}


### Button Groups

Buttons can be joined to form several buttons. Buttons can be down with `button-direction`.

<div class="margin-bottom:6">
  <div class="buttons border-radius:round">
    <button class="button button-size:2 f2 button-style:outline">1</button>
    <button class="button button-size:2 fi2et button-style:outline">2</button>
    <button class="button button-size:2 f2ple button-style:outline">3</button>
    <button class="button button-size:2 f2avy button-style:outline">4</button>
  </div>
</div>

<div class="margin-bottom:6">
  <div class="buttons border-radius:round buttons-direction:down">
    <button class="button fill:pink button-style:outline">1</button>
    <button class="button fill:violet button-style:outline">2</button>
    <button class="button fill:purple button-style:outline">3</button>
    <button class="button fill:navy button-style:outline">4</button>
  </div>
</div>

<div class="margin-bottom:6">
  <div class="buttons border-radius:round buttons-direction:down">
    <button class="button">1</button>
    <button class="button">2</button>
    <button class="button">3</button>
  </div>
</div>

<div class="margin-bottom:6">
  <div class="buttons buttons-direction@md:down">
    <button class="button">1</button>
    <button class="button">2</button>
    <button class="button">3</button>
  </div>
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="buttons border-radius:round">
  <button class="button button-size:2 fill:pink button-style:outline">1</button>
  <button class="button button-size:2 fill:violet button-style:outline">2</button>
  <button class="button button-size:2 fill:purple button-style:outline">3</button>
  <button class="button button-size:2 fill:navy button-style:outline">4</button>
</div>

<div class="buttons border-radius:round buttons-direction:down">
  <button class="button fill:pink button-style:outline">1</button>
  <button class="button fill:violet button-style:outline">2</button>
  <button class="button fill:purple button-style:outline">3</button>
  <button class="button fill:navy button-style:outline">4</button>
</div>

<div class="buttons border-radius:round buttons-direction:down">
  <button class="button">1</button>
  <button class="button">2</button>
  <button class="button">3</button>
</div>

<div class="buttons buttons-direction@md:down">
  <button class="button">1</button>
  <button class="button">2</button>
  <button class="button">3</button>
</div>
```
{{% /codeblock %}}

### Colors

Use the `fill` component to apply different color your buttons.

<button class="button button-style:outline fill:red margin-bottom:6">Button</button>
<button class="button button-style:outline fill:pink margin-bottom:6">Button</button>
<button class="button button-style:outline fill:violet margin-bottom:6">Button</button>
<button class="button button-style:outline fill:purple margin-bottom:6">Button</button>
<button class="button button-style:outline fill:navy margin-bottom:6">Button</button>
<button class="button button-style:outline fill:blue margin-bottom:6">Button</button>
<button class="button button-style:outline fill:teal margin-bottom:6">Button</button>
<button class="button button-style:outline fill:green margin-bottom:6">Button</button>
<button class="button button-style:outline fill:lime margin-bottom:6">Button</button>
<button class="button button-style:outline fill:yellow margin-bottom:6">Button</button>
<button class="button button-style:outline fill:orange margin-bottom:6">Button</button>
<button class="button button-style:outline fill:brown margin-bottom:6">Button</button>
<button class="button button-style:outline fill:grey margin-bottom:6">Button</button>
<button class="button button-style:outline fill:white margin-bottom:6">Button</button>
<button class="button button-style:outline fill:black margin-bottom:6">Button</button>

<button class="button button-style:flat fill:red margin-bottom:6">Button</button>
<button class="button button-style:flat fill:pink margin-bottom:6">Button</button>
<button class="button button-style:flat fill:violet margin-bottom:6">Button</button>
<button class="button button-style:flat fill:purple margin-bottom:6">Button</button>
<button class="button button-style:flat fill:navy margin-bottom:6">Button</button>
<button class="button button-style:flat fill:blue margin-bottom:6">Button</button>
<button class="button button-style:flat fill:teal margin-bottom:6">Button</button>
<button class="button button-style:flat fill:green margin-bottom:6">Button</button>
<button class="button button-style:flat fill:lime margin-bottom:6">Button</button>
<button class="button button-style:flat fill:yellow margin-bottom:6">Button</button>
<button class="button button-style:flat fill:orange margin-bottom:6">Button</button>
<button class="button button-style:flat fill:brown margin-bottom:6">Button</button>
<button class="button button-style:flat fill:grey margin-bottom:6">Button</button>
<button class="button button-style:flat fill:white margin-bottom:6">Button</button>
<button class="button button-style:flat fill:black margin-bottom:6">Button</button>

<button class="button fill:red margin-bottom:6">Button</button>
<button class="button fill:pink margin-bottom:6">Button</button>
<button class="button fill:violet margin-bottom:6">Button</button>
<button class="button fill:purple margin-bottom:6">Button</button>
<button class="button fill:navy margin-bottom:6">Button</button>
<button class="button fill:blue margin-bottom:6">Button</button>
<button class="button fill:teal margin-bottom:6">Button</button>
<button class="button fill:green margin-bottom:6">Button</button>
<button class="button fill:lime margin-bottom:6">Button</button>
<button class="button fill:yellow margin-bottom:6">Button</button>
<button class="button fill:orange margin-bottom:6">Button</button>
<button class="button fill:brown margin-bottom:6">Button</button>
<button class="button fill:grey margin-bottom:6">Button</button>
<button class="button fill:white margin-bottom:6">Button</button>
<button class="button fill:black margin-bottom:6">Button</button>

<button class="button elevate fill:red margin-bottom:6">Button</button>
<button class="button elevate fill:pink margin-bottom:6">Button</button>
<button class="button elevate fill:violet margin-bottom:6">Button</button>
<button class="button elevate fill:purple margin-bottom:6">Button</button>
<button class="button elevate fill:navy margin-bottom:6">Button</button>
<button class="button elevate fill:blue margin-bottom:6">Button</button>
<button class="button elevate fill:teal margin-bottom:6">Button</button>
<button class="button elevate fill:green margin-bottom:6">Button</button>
<button class="button elevate fill:lime margin-bottom:6">Button</button>
<button class="button elevate fill:yellow margin-bottom:6">Button</button>
<button class="button elevate fill:orange margin-bottom:6">Button</button>
<button class="button elevate fill:brown margin-bottom:6">Button</button>
<button class="button elevate fill:grey margin-bottom:6">Button</button>
<button class="button elevate fill:white margin-bottom:6">Button</button>
<button class="button elevate fill:black margin-bottom:6">Button</button>

<button class="button fill:white elevate button-grow:3 border-radius:round color:grey-d1 margin-bottom:6">Button</button>
<button class="button fill:blue elevate button-grow:3 border-radius:round margin-bottom:6">Button</button>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<button class="button fill:red">Button</button>
<button class="button fill:pink">Button</button>
<button class="button fill:violet">Button</button>
<button class="button fill:purple">Button</button>
<button class="button fill:navy">Button</button>
<button class="button fill:blue">Button</button>
<button class="button fill:teal">Button</button>
<button class="button fill:green">Button</button>
<button class="button fill:lime">Button</button>
<button class="button fill:yellow">Button</button>
<button class="button fill:orange">Button</button>
<button class="button fill:brown">Button</button>
<button class="button fill:grey">Button</button>
<button class="button fill:white">Button</button>
<button class="button fill:black">Button</button>
```
{{% /codeblock %}}

### Local Variables

You can override styling using the following local variables.

{{% codeblock key="language" definition="css" margin="bottom" %}}
```css
$button-sizes: 5 !default;

:root {
  --button-outline-weight: 2px;
  --button-radius: var(--radius);
  --button-font-family: var(--font-family);
  --button-font-size: var(--micro);
  --button-font-weight: var(--medium);
}
```
{{% /codeblock %}}

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
      <code>button-style</code>
    </td>
    <td data-label="Attributes">
      <code>:outline</code><code>:flat</code>
    </td>
    <td data-label="Responsive">
      No
    </td>
    <td class="row:reverse">
      Outline or flat style buttons
    </td>
  </tr>
  <tr>
    <td data-label="Properties">
      <code>button-size</code>
    </td>
    <td data-label="Attributes">
      <code>:1</code> ... <code>:5</code>
    </td>
    <td data-label="Responsive">
      No
    </td>
    <td class="row:reverse">
      Set button size
    </td>
  </tr>
  <tr>
    <td data-label="Properties">
      <code>button-grow</code>
    </td>
    <td data-label="Attributes">
      <code>:1</code> ... <code>:5</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td class="row:reverse">
      Set horizontal padding
    </td>
  </tr>
  <tr>
    <td data-label="Properties">
      <code>buttons-direction</code>
    </td>
    <td data-label="Attributes">
      <code>:down</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td class="row:reverse">
      Downward buttons
    </td>
  </tr>
</table>
