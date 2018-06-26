---
title: "Button"
date: 2018-04-11T09:16:45+12:00
draft: false
description: "Colorful and juicy button component in all shapes and sizes."

---

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

<div class="distribute-y:1 margin-bottom:2">
  <button class="button">Default</button><br>
  <button class="button button-grow:1">Grow 1</button><br>
  <button class="button button-grow:2">Grow 2</button><br>
  <button class="button button-grow:3">Grow 3</button><br>
  <button class="button button-grow:4">Grow 4</button><br>
  <button class="button button-grow:5">Grow 5</button><br>
  <button class="button button:fluid">Fluid</button>
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<button class="button">Default</button>
<button class="button button-grow:1">Grow 1</button>
<button class="button button-grow:2">Grow 2</button>
<button class="button button-grow:3">Grow 3</button>
<button class="button button-grow:4">Grow 4</button>
<button class="button button-grow:5">Grow 5</button>
<button class="button button:fluid">Fluid</button>
```
{{% /codeblock %}}

##### Shapes

You can apply differently shaped corners with the border utility.

<div class="margin-bottom:2">
  <button class="button">Default</button>
  <button class="button border:sharp">Sharp</button>
  <button class="button border:round">Round</button>
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<button class="button">Default</button>
<button class="button border:sharp">Sharp</button>
<button class="button border:round">Round</button>
```
{{% /codeblock %}}

##### Styles

There are 3 different styles of buttons, standard, outline and elevated.

<div class="margin-bottom:2">
  <button class="button button-grow:2">Default</button>
  <button class="button button-grow:2 button-style:outline">Outline</button>
  <button class="button button-grow:2 button-style:elevate">Elevated</button>
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<button class="button button-grow:2">Default</button>
<button class="button button-grow:2 button-style:outline">Outline</button>
<button class="button button-grow:2 button-style:elevate">Elevated</button>
```
{{% /codeblock %}}

##### Button Weights

Buttons can have different font weights with the font component.

<div class="u-spread-x-1 margin-bottom:2">
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

Buttons can be joined to form several buttons. Buttons can be vertical `button-direction`.

<div class="margin-bottom:2">
  <div class="buttons">
    <button class="button">1</button>
    <button class="button">2</button>
    <button class="button">3</button>
  </div>
</div>

<div class="margin-bottom:2">
  <div class="buttons buttons-style:round buttons-direction:vertical">
    <button class="button">1</button>
    <button class="button">2</button>
    <button class="button">3</button>
  </div>
</div>

<div class="margin-bottom:2">
  <div class="buttons -round -vertical">
    <button class="button">1</button>
    <button class="button">2</button>
    <button class="button">3</button>
  </div>
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="buttons">
  <button class="button">1</button>
  <button class="button">2</button>
  <button class="button">3</button>
</div>

<div class="buttons -round -vertical-tb">
  <button class="button">1</button>
  <button class="button">2</button>
  <button class="button">3</button>
</div>

<div class="buttons -round -vertical">
  <button class="button">1</button>
  <button class="button">2</button>
  <button class="button">3</button>
</div>
```
{{% /codeblock %}}

##### Colors

There are 10 colors available to choose from.

<div class="buttons buttons-direction:vertical -inline-tb margin-bottom:2">
  <a class="button">Button</a>
  <button class="button fill:primary button-color:green">Button</button>
  <button class="button fill:secondary">Button</button>
  <button class="button fill:red">Button</button>
  <button class="button fill:orange">Button</button>
  <button class="button fill:yellow">Button</button>
  <button class="button fill:green">Button</button>
  <button class="button fill:blue">Button</button>
  <button class="button fill:purple">Button</button>
  <button class="button fill:black">Button</button>
</div>

<div class="buttons margin-bottom:2">
  <a class="button">Button</a>
  <button class="button fill:primary button-color:green">Button</button>
  <button class="button fill:secondary">Button</button>
  <button class="button fill:red">Button</button>
  <button class="button fill:orange">Button</button>
  <button class="button fill:yellow">Button</button>
  <button class="button fill:green">Button</button>
  <button class="button fill:blue">Button</button>
  <button class="button fill:purple">Button</button>
  <button class="button fill:black">Button</button>
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<button class="button">Button</button>
<button class="button fill:primary">Button</button>
<button class="button fill:secondary">Button</button>
<button class="button fill:red">Button</button>
<button class="button fill:orange">Button</button>
<button class="button fill:yellow">Button</button>
<button class="button fill:green">Button</button>
<button class="button fill:blue">Button</button>
<button class="button fill:purple">Button</button>
<button class="button fill:black">Button</button>
```
{{% /codeblock %}}

##### Outline Buttons

Empty buttons with outlines are also available using the `-outline` modifier.

<div class="buttons buttons-direction:ve2rtical -inline-tb margin-bottom:2">
  <button class="button button-style:outline fill:blue button-color:blue">Button</button>
  <button class="button button-style:outline fill:red">Button</button>
  <button class="button button-style:outline fill:orange">Button</button>
  <button class="button button-style:outline fill:yellow">Button</button>
  <button class="button button-style:outline fill:green">Button</button>
  <button class="button button-style:outline fill:blue">Button</button>
  <button class="button button-style:outline fill:purple">Button</button>
  <button class="button button-style:outline fill:black">Button</button>
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<button class="button -outline">Button</button>
<button class="button -outline -accent">Button</button>
<button class="button -outline -red">Button</button>
<button class="button -outline -orange">Button</button>
<button class="button -outline -yellow">Button</button>
<button class="button -outline -green">Button</button>
<button class="button -outline -blue">Button</button>
<button class="button -outline -purple">Button</button>
<button class="button -outline -black">Button</button>
<button class="button -outline -white">Button</button>
```
{{% /codeblock %}}
