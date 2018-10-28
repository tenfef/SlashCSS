+++
title = "Button"
date = "2018-04-11T09:16:45+12:00"
family = "Single"
draft = false
description = "Colorful and juicy button component in all shapes and sizes."
+++
### Basic Button

A standard button

<button class="button button-color:blue">Button</button>

```html
<button class="button">
  Button
</button>
```

### Sizes

Buttons comes in various sizes, use standard size modifiers to transform its size.

<div class="margin-bottom:u6">
  <button class="button button-color:red button-size:xs">Button</button>
  <button class="button button-color:pink button-size:sm">Button</button>
  <button class="button button-color:violet button-size:md">Button</button>
  <button class="button button-color:purple button-size:lg">Button</button>
  <button class="button button-color:navy button-size:xl">Button</button>
</div>

```html
<button class="button button-size:xs">Button</button>
<button class="button button-size:sm">Button</button>
<button class="button button-size:md">Button</button>
<button class="button button-size:lg">Button</button>
<button class="button button-size:xl">Button</button>
```

### Growing Buttons

Buttons can vary in width.

<div class="distribute-y:u4 margin-bottom:u6">
  <button class="button">Default</button><br>
  <button class="button button-grow:u6 button-color:white button-style:elevate">U6</button><br>
  <button class="button button-grow:u8 button-color:white button-style:elevate">U8</button><br>
  <button class="button button-grow:u10 button-color:white button-style:elevate">U10</button><br>
  <button class="button button-grow:u12 button-color:white button-style:elevate">U12</button><br>
  <button class="button button-grow:u14 button-color:white button-style:elevate">U14</button><br>
  <button class="button width:100% button-color:white button-style:elevate">Fluid</button>
</div>

```html
<button class="button">Default</button>
<button class="button button-grow:u6">U6</button>
<button class="button button-grow:u8">U8</button>
<button class="button button-grow:u10">U10</button>
<button class="button button-grow:u12">U12</button>
<button class="button button-grow:u14">U14</button>
<button class="button width:100%">Fluid</button>
```

### Shapes

You can apply different corners with the `border` component.

<div class="margin-bottom:u6">
  <button class="button">Default</button>
  <button class="button border-radius:sharp">Sharp</button>
  <button class="button border-radius:round">Round</button>
</div>

```html
<button class="button">Default</button>
<button class="button border-radius:sharp">Sharp</button>
<button class="button border-radius:round">Round</button>
```

### Icon Buttons

Buttons can contain icons.

<div class="margin-bottom:u6">
  <button class="button button-style:outline font-size:body font-case:none">
    <i class="fas fa-cloud-upload-alt margin-right:u4"></i>
    Upload File
  </button>
</div>

```html
<button class="button button-style:outline font-size:body font-case:none">
  <div class="button/icon">
    <i class="fas fa-cloud-upload-alt margin-right:u2"></i>
  </div>
  Upload File
</button>
```

### Styles

There are 4 different styles of buttons, default, outline and elevated.

<div class="margin-bottom:u6">
  <button class="button margin-bottom:u6">Default</button>
  <button class="button button-style:elevate margin-bottom:u6">Elevated</button>
  <button class="button button-style:outline margin-bottom:u6">Outline</button>
  <button class="button button-style:flat">Flat</button>
</div>

```html
<button class="button">Default</button>
<button class="button button-style:elevate">Elevated</button>
<button class="button button-style:outline">Outline</button>
<button class="button button-style:flat">Flat</button>
```

### Button Weights

Buttons can have different font weights with the font component.

<div class="margin-bottom:u6">
  <button class="button font-weight:regular">Regular</button>
  <button class="button font-weight:medium">Medium</button>
  <button class="button font-weight:bold">Bold</button>
</div>

```html
<button class="button font-weight:regular">Regular</button>
<button class="button font-weight:medium">Medium</button>
<button class="button font-weight:bold">Bold</button>
```


### Button Groups

Buttons can be joined to form several buttons. Buttons can also be vertical.

<div class="margin-bottom:u6">
  <div class="buttons border-radius:round">
    <button class="button button-style:outline">1</button>
    <button class="button button-style:outline">2</button>
    <button class="button button-style:outline">3</button>
    <button class="button button-style:outline">4</button>
  </div>
</div>

<div class="margin-bottom:u6">
  <div class="buttons border-radius:round buttons:pile">
    <button class="button button-color:pink button-style:outline">1</button>
    <button class="button button-color:violet button-style:outline">2</button>
    <button class="button button-color:purple button-style:outline">3</button>
    <button class="button button-color:navy button-style:outline">4</button>
  </div>
</div>

<div class="margin-bottom:u6">
  <div class="buttons border-radius:round buttons:pile">
    <button class="button button-color:green">1</button>
    <button class="button button-color:green">2</button>
    <button class="button button-color:green">3</button>
  </div>
</div>

<div class="margin-bottom:u6">
  <div class="buttons buttons-direction@md:down">
    <button class="button">1</button>
    <button class="button">2</button>
    <button class="button">3</button>
  </div>
</div>

```html
<div class="buttons border-radius:round">
  <button class="button button-color:pink button-style:outline">1</button>
  <button class="button button-color:violet button-style:outline">2</button>
  <button class="button button-color:purple button-style:outline">3</button>
  <button class="button button-color:navy button-style:outline">4</button>
</div>

<div class="buttons border-radius:round buttons:pile">
  <button class="button button-color:pink button-style:outline">1</button>
  <button class="button button-color:violet button-style:outline">2</button>
  <button class="button button-color:purple button-style:outline">3</button>
  <button class="button button-color:navy button-style:outline">4</button>
</div>

<div class="buttons border-radius:round buttons:pile">
  <button class="button button-color:green">1</button>
  <button class="button button-color:green">2</button>
  <button class="button button-color:green">3</button>
</div>

<div class="buttons">
  <button class="button">1</button>
  <button class="button">2</button>
  <button class="button">3</button>
</div>
```

### Colors

Use `button-color` to apply different color your buttons. Tonal colors are not available.

<button class="button button-color:red margin-bottom:u6">Button</button>
<button class="button button-color:pink margin-bottom:u6">Button</button>
<button class="button button-color:violet margin-bottom:u6">Button</button>
<button class="button button-color:purple margin-bottom:u6">Button</button>
<button class="button button-color:navy margin-bottom:u6">Button</button>
<button class="button button-color:blue margin-bottom:u6">Button</button>
<button class="button button-color:teal margin-bottom:u6">Button</button>
<button class="button button-color:green margin-bottom:u6">Button</button>
<button class="button button-color:lime margin-bottom:u6">Button</button>
<button class="button button-color:yellow margin-bottom:u6">Button</button>
<button class="button button-color:orange margin-bottom:u6">Button</button>
<button class="button button-color:brown margin-bottom:u6">Button</button>
<button class="button button-color:grey margin-bottom:u6">Button</button>
<button class="button button-color:white margin-bottom:u6">Button</button>
<button class="button button-color:black margin-bottom:u6">Button</button>
<button class="button button-color:blue margin-bottom:u6">Button</button>
<button class="button button-color:primary margin-bottom:u6">Button</button>
<button class="button button-color:secondary margin-bottom:u6">Button</button>
<button class="button button-color:tertiary margin-bottom:u6">Button</button>

```html
<button class="button button-color:red">Button</button>
<button class="button button-color:pink">Button</button>
<button class="button button-color:violet">Button</button>
<button class="button button-color:purple">Button</button>
<button class="button button-color:navy">Button</button>
<button class="button button-color:blue">Button</button>
<button class="button button-color:teal">Button</button>
<button class="button button-color:green">Button</button>
<button class="button button-color:lime">Button</button>
<button class="button button-color:yellow">Button</button>
<button class="button button-color:orange">Button</button>
<button class="button button-color:brown">Button</button>
<button class="button button-color:grey">Button</button>
<button class="button button-color:white">Button</button>
<button class="button button-color:black">Button</button>
<button class="button button-color:primary">Button</button>
<button class="button button-color:secondary">Button</button>
<button class="button button-color:tertiary">Button</button>
```
### Local Variables

You can override this component using the following local variables.

```css
$button-widths: 5 !default;

:root {
  --button-outline-weight: 1px;
  --button-radius: 5px;
  --button-font-family: var(--font-family);
  --button-font-size: var(--micro);
  --button-font-weight: var(--medium);
}
```

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
      <code>:outline</code><code>:flat</code><code>:elevate</code>
    </td>
    <td data-label="Responsive">
      No
    </td>
    <td>
      Set button style
    </td>
  </tr>
  <tr>
    <td data-label="Properties">
      <code>button-color</code>
    </td>
    <td data-label="Attributes">
      <code>:[base color]</code>
    </td>
    <td data-label="Responsive">
      No
    </td>
    <td>
      Set button color
    </td>
  </tr>
  <tr>
    <td data-label="Properties">
      <code>button-size</code>
    </td>
    <td data-label="Attributes">
      <code>:xs</code> <code>:sm</code> <code>:md</code> <code>:lg</code> <code>:xl</code>
    </td>
    <td data-label="Responsive">
      No
    </td>
    <td>
      Set button size
    </td>
  </tr>
  <tr>
    <td data-label="Properties">
      <code>button-grow</code>
    </td>
    <td data-label="Attributes">
      <code>:u6</code> <code>:u8</code> <code>:u10</code> <code>:u12</code> <code>:u14</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td>
      Set horizontal padding
    </td>
  </tr>
  <tr>
    <td data-label="Properties">
      <code>buttons</code>
    </td>
    <td data-label="Attributes">
      <code>:pile</code>
    </td>
    <td data-label="Responsive">
      No
    </td>
    <td>
      Vertically stack buttons
    </td>
  </tr>
</table>
