+++
title = "Button"
date = "2018-04-11T09:16:45+12:00"
family = "Single"
draft = false
description = "Colorful and juicy button component in all shapes and sizes."
+++
### Basic Button

A standard button

<button class="button fill:blue">Button</button>

```html
<button class="button">
  Button
</button>
```

### Sizes

Buttons comes in various sizes, use standard size modifiers to transform its size.

<div class="margin-bottom:u6">
  <button class="button fill:red button-size:xs">Button</button>
  <button class="button fill:pink button-size:sm">Button</button>
  <button class="button fill:violet button-size:md">Button</button>
  <button class="button fill:purple button-size:lg">Button</button>
  <button class="button fill:navy button-size:xl">Button</button>
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

<div class="distribute-y:1 margin-bottom:u6">
  <button class="button">Default</button><br>
  <button class="button button-grow:u2 fill:white elevate">U2</button><br>
  <button class="button button-grow:u4 fill:white elevate">U4</button><br>
  <button class="button button-grow:u6 fill:white elevate">U6</button><br>
  <button class="button button-grow:u8 fill:white elevate">U8</button><br>
  <button class="button button-grow:u10 fill:white elevate">U10</button><br>
  <button class="button width:100% fill:white elevate">Fluid</button>
</div>

```html
<button class="button">Default</button>
<button class="button button-grow:u2">U2</button>
<button class="button button-grow:u4">U4</button>
<button class="button button-grow:u6">U6</button>
<button class="button button-grow:u8">U8</button>
<button class="button button-grow:u10">U10</button>
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
  <button class="button elevate margin-bottom:u6">Elevated</button>
  <button class="button button-style:outline margin-bottom:u6">Outline</button>
  <button class="button button-style:flat">Flat</button>
</div>

```html
<button class="button">Default</button>
<button class="button elevate">Elevated</button>
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
  <div class="buttons border-radius:round buttons:stack">
    <button class="button fill:pink button-style:outline">1</button>
    <button class="button fill:violet button-style:outline">2</button>
    <button class="button fill:purple button-style:outline">3</button>
    <button class="button fill:navy button-style:outline">4</button>
  </div>
</div>

<div class="margin-bottom:u6">
  <div class="buttons border-radius:round buttons:stack">
    <button class="button fill:green">1</button>
    <button class="button fill:green">2</button>
    <button class="button fill:green">3</button>
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
  <button class="button fill:pink button-style:outline">1</button>
  <button class="button fill:violet button-style:outline">2</button>
  <button class="button fill:purple button-style:outline">3</button>
  <button class="button fill:navy button-style:outline">4</button>
</div>

<div class="buttons border-radius:round buttons:stack">
  <button class="button fill:pink button-style:outline">1</button>
  <button class="button fill:violet button-style:outline">2</button>
  <button class="button fill:purple button-style:outline">3</button>
  <button class="button fill:navy button-style:outline">4</button>
</div>

<div class="buttons border-radius:round buttons:stack">
  <button class="button fill:green">1</button>
  <button class="button fill:green">2</button>
  <button class="button fill:green">3</button>
</div>

<div class="buttons buttons-direction@md:down">
  <button class="button">1</button>
  <button class="button">2</button>
  <button class="button">3</button>
</div>
```

### Colors

Use the `fill` component to apply different color your buttons.

<button class="button button-style:outline fill:red margin-bottom:u6">Button</button>
<button class="button button-style:outline fill:pink margin-bottom:u6">Button</button>
<button class="button button-style:outline fill:violet margin-bottom:u6">Button</button>
<button class="button button-style:outline fill:purple margin-bottom:u6">Button</button>
<button class="button button-style:outline fill:navy margin-bottom:u6">Button</button>
<button class="button button-style:outline fill:blue margin-bottom:u6">Button</button>
<button class="button button-style:outline fill:teal margin-bottom:u6">Button</button>
<button class="button button-style:outline fill:green margin-bottom:u6">Button</button>
<button class="button button-style:outline fill:lime margin-bottom:u6">Button</button>
<button class="button button-style:outline fill:yellow margin-bottom:u6">Button</button>
<button class="button button-style:outline fill:orange margin-bottom:u6">Button</button>
<button class="button button-style:outline fill:brown margin-bottom:u6">Button</button>
<button class="button button-style:outline fill:grey margin-bottom:u6">Button</button>
<button class="button button-style:outline fill:white margin-bottom:u6">Button</button>
<button class="button button-style:outline fill:black margin-bottom:u6">Button</button>

<button class="button button-style:flat fill:red margin-bottom:u6">Button</button>
<button class="button button-style:flat fill:pink margin-bottom:u6">Button</button>
<button class="button button-style:flat fill:violet margin-bottom:u6">Button</button>
<button class="button button-style:flat fill:purple margin-bottom:u6">Button</button>
<button class="button button-style:flat fill:navy margin-bottom:u6">Button</button>
<button class="button button-style:flat fill:blue margin-bottom:u6">Button</button>
<button class="button button-style:flat fill:teal margin-bottom:u6">Button</button>
<button class="button button-style:flat fill:green margin-bottom:u6">Button</button>
<button class="button button-style:flat fill:lime margin-bottom:u6">Button</button>
<button class="button button-style:flat fill:yellow margin-bottom:u6">Button</button>
<button class="button button-style:flat fill:orange margin-bottom:u6">Button</button>
<button class="button button-style:flat fill:brown margin-bottom:u6">Button</button>
<button class="button button-style:flat fill:grey margin-bottom:u6">Button</button>
<button class="button button-style:flat fill:white margin-bottom:u6">Button</button>
<button class="button button-style:flat fill:black margin-bottom:u6">Button</button>

<button class="button fill:red margin-bottom:u6">Button</button>
<button class="button fill:pink margin-bottom:u6">Button</button>
<button class="button fill:violet margin-bottom:u6">Button</button>
<button class="button fill:purple margin-bottom:u6">Button</button>
<button class="button fill:navy margin-bottom:u6">Button</button>
<button class="button fill:blue margin-bottom:u6">Button</button>
<button class="button fill:teal margin-bottom:u6">Button</button>
<button class="button fill:green margin-bottom:u6">Button</button>
<button class="button fill:lime margin-bottom:u6">Button</button>
<button class="button fill:yellow margin-bottom:u6">Button</button>
<button class="button fill:orange margin-bottom:u6">Button</button>
<button class="button fill:brown margin-bottom:u6">Button</button>
<button class="button fill:grey margin-bottom:u6">Button</button>
<button class="button fill:white margin-bottom:u6">Button</button>
<button class="button fill:black margin-bottom:u6">Button</button>

<button class="button elevate fill:red margin-bottom:u6">Button</button>
<button class="button elevate fill:pink margin-bottom:u6">Button</button>
<button class="button elevate fill:violet margin-bottom:u6">Button</button>
<button class="button elevate fill:purple margin-bottom:u6">Button</button>
<button class="button elevate fill:navy margin-bottom:u6">Button</button>
<button class="button elevate fill:blue margin-bottom:u6">Button</button>
<button class="button elevate fill:teal margin-bottom:u6">Button</button>
<button class="button elevate fill:green margin-bottom:u6">Button</button>
<button class="button elevate fill:lime margin-bottom:u6">Button</button>
<button class="button elevate fill:yellow margin-bottom:u6">Button</button>
<button class="button elevate fill:orange margin-bottom:u6">Button</button>
<button class="button elevate fill:brown margin-bottom:u6">Button</button>
<button class="button elevate fill:grey margin-bottom:u6">Button</button>
<button class="button elevate fill:white margin-bottom:u6">Button</button>
<button class="button elevate fill:black margin-bottom:u6">Button</button>

<button class="button fill:white elevate button-grow:u10 border-radius:round color:grey-d1 margin-bottom:u6">Button</button>
<button class="button fill:blue elevate button-grow:u10 border-radius:round margin-bottom:u6">Button</button>

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
      <code>:xs</code> <code>:sm</code> <code>:md</code> <code>:lg</code> <code>:xl</code>
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
      <code>:u2</code> <code>:u4</code> <code>:u6</code> <code>:u8</code> <code>:u10</code>
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
      <code>buttons</code>
    </td>
    <td data-label="Attributes">
      <code>:stack</code>
    </td>
    <td data-label="Responsive">
      No
    </td>
    <td class="row:reverse">
      Vertically stack buttons
    </td>
  </tr>
</table>
