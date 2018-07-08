+++
title = "Button"
date = "2018-04-11T09:16:45+12:00"
draft = false
description = "Colorful and juicy button component in all shapes and sizes."
+++

##### Basic Button

A standard button

<button class="button">Button</button>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<button class="button">
  Button
</button>
```
{{% /codeblock %}}

##### Sizes

Buttons comes in various sizes, use standard size modifiers to transform its size.

<div class="margin-bottom:2">
  <button class="button button-size:1">Button</button>
  <button class="button button-size:2">Button</button>
  <button class="button button-size:3">Button</button>
  <button class="button button-size:4">Button</button>
  <button class="button button-size:5">Button</button>
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<button class="button button-size:1">Button</button>
<button class="button button-size:2">Button</button>
<button class="button button-size:3">Button</button>
<button class="button button-size:4">Button</button>
<button class="button button-size:5">Button</button>
```
{{% /codeblock %}}

##### Growing Buttons

Buttons can vary in width.

<div class="distribute-down:1 margin-bottom:2">
  <button class="button">Default</button><br>
  <button class="button button-grow:1">Grow 1</button><br>
  <button class="button button-grow:2">Grow 2</button><br>
  <button class="button button-grow:3">Grow 3</button><br>
  <button class="button button-grow:4">Grow 4</button><br>
  <button class="button button-grow:5">Grow 5</button><br>
  <button class="button width:fluid">Fluid</button>
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<button class="button">Default</button>
<button class="button button-grow:1">Grow 1</button>
<button class="button button-grow:2">Grow 2</button>
<button class="button button-grow:3">Grow 3</button>
<button class="button button-grow:4">Grow 4</button>
<button class="button button-grow:5">Grow 5</button>
<button class="button width:fluid">Fluid</button>
```
{{% /codeblock %}}

##### Shapes

You can apply different corners with the `border` component.

<div class="margin-bottom:2">
  <button class="button">Default</button>
  <button class="button border-style:sharp">Sharp</button>
  <button class="button border-style:round">Round</button>
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<button class="button">Default</button>
<button class="button border-style:sharp">Sharp</button>
<button class="button border-style:round">Round</button>
```
{{% /codeblock %}}

##### Styles

There are 3 different styles of buttons, default, outline and button-style:physicald.

<div class="margin-bottom:2">
  <button class="button button-grow:2">Default</button>
  <button class="button button-grow:2 button-style:outline">Outline</button>
  <button class="button button-grow:2 button-style:physical">Elevated</button>
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<button class="button button-grow:2">Default</button>
<button class="button button-grow:2 button-style:outline">Outline</button>
<button class="button button-grow:2 button-style:physical">Elevated</button>
```
{{% /codeblock %}}

##### Button Weights

Buttons can have different font weights with the font component.

<div class="margin-bottom:2">
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


##### Button Groups

Buttons can be joined to form several buttons. Buttons can be down with `button-direction`.

<div class="margin-bottom:2">
  <div class="buttons">
    <button class="button button-size:2">1</button>
    <button class="button button-size:2">2</button>
    <button class="button button-size:2">3</button>
  </div>
</div>

<div class="margin-bottom:2">
  <div class="buttons border-style:round buttons-direction:down">
    <button class="button">1</button>
    <button class="button">2</button>
    <button class="button">3</button>
  </div>
</div>

<div class="margin-bottom:2">
  <div class="buttons border-style:sharp buttons-direction-md:down">
    <button class="button">1</button>
    <button class="button">2</button>
    <button class="button">3</button>
  </div>
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="buttons">
  <button class="button button-size:2">1</button>
  <button class="button button-size:2">2</button>
  <button class="button button-size:2">3</button>
</div>

<div class="buttons border-style:round buttons-direction:down">
  <button class="button">1</button>
  <button class="button">2</button>
  <button class="button">3</button>
</div>

<div class="buttons border-style:sharp buttons-direction-md:down">
  <button class="button">1</button>
  <button class="button">2</button>
  <button class="button">3</button>
</div>
```
{{% /codeblock %}}

##### Colors

Use the `fill` component to apply different color your buttons.

<button class="button button-style:physical fill:primary margin-bottom:2">Button</button>
<button class="button button-style:physical fill:secondary margin-bottom:2">Button</button>
<button class="button button-style:physical fill:red margin-bottom:2">Button</button>
<button class="button button-style:physical fill:orange margin-bottom:2">Button</button>
<button class="button button-style:physical fill:yellow margin-bottom:2">Button</button>
<button class="button button-style:physical fill:green margin-bottom:2">Button</button>
<button class="button button-style:physical fill:blue margin-bottom:2">Button</button>
<button class="button button-style:physical fill:purple margin-bottom:2">Button</button>
<button class="button button-style:physical fill:black margin-bottom:2">Button</button>
<button class="button button-style:physical fill:grey margin-bottom:2">Button</button>
<button class="button button-style:physical fill:white color:black margin-bottom:2">Button</button>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<button class="button button-style:physical fill:primary">Button</button>
<button class="button button-style:physical fill:secondary">Button</button>
<button class="button button-style:physical fill:red">Button</button>
<button class="button button-style:physical fill:orange">Button</button>
<button class="button button-style:physical fill:yellow">Button</button>
<button class="button button-style:physical fill:green">Button</button>
<button class="button button-style:physical fill:blue">Button</button>
<button class="button button-style:physical fill:purple">Button</button>
<button class="button button-style:physical fill:black">Button</button>
<button class="button button-style:physical fill:grey">Button</button>
<button class="button button-style:physical fill:white color:black">Button</button>
```
{{% /codeblock %}}

##### Local Root Variables

You can override styling using the following local root variables.

{{% codeblock key="language" definition="css" margin="bottom" %}}
```css
:root {
  --button-outline-weight: 2px;
  --button-radius: var(--radius);
  --button-font-family: var(--font-family);
  --button-font-size: var(--micro);
  --button-font-weight: var(--medium);
}
```
{{% /codeblock %}}

##### Settings

The following settings are available.

<table class="table width:fluid table:pile">
  <thead>
    <tr>
      <th>
        Properties
      </th>
      <th>
        Attributes
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
      <code>:outline</code>
    </td>
    <td data-label="Responsive">
      No
    </td>
    <td class="row:reverse">
      Outline button style
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
      <code>button-direction</code>
    </td>
    <td data-label="Attributes">
      <code>:down</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td class="row:reverse">
      Enable down buttons
    </td>
  </tr>
</table>
