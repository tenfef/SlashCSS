+++
title = "Notice"
date = "2018-04-11T09:16:45+12:00"
family = "Module"
draft = false
description = "The notice component is useful for visually displaying temporary content or information."
+++

### Basic Usage

Defined with the class `notice` initialized with javascript. The `notice/close` is required.

<div class="notice is-active">
  <div class="notice/content">
    <span class="label fill:orange margin-right:u2">NEW</span>
    <span class="font-size:body">Sample Notification</span>
  </div>

  <div class="notice/close">
    <span></span>
  </div>
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="notice is-active">
  <div class="notice/content">
    <span class="label fill:blue margin-right:u2">NEW</span>
    <span class="font-size:body">Sample Notification</span>
  </div>

  <div class="notice/close">
    <span></span>
  </div>
</div>
```

{{% codeblock key="initializing" definition="javascript" margin="top" %}}
```javascript
var notice = new Notice();
```
{{% /codeblock %}}

{{% /codeblock %}}

### Colors

You can change the background color using the `fill` component.

<div class="notice fill:red margin-bottom:u2 is-active">
  <div class="notice/content">
    <span class="label fill:blue margin-right:u2">NEW</span>
    <span class="font-size:body">Sample Notification</span>
  </div>

  <div class="notice/close">
    <span></span>
  </div>
</div>

<div class="notice fill:blue margin-bottom:u2 is-active">
  <div class="notice/content">
    <span class="label fill:blue margin-right:u2">NEW</span>
    <span class="font-size:body">Sample Notification</span>
  </div>

  <div class="notice/close">
    <span></span>
  </div>
</div>

<div class="notice fill:orange margin-bottom:u2 is-active">
  <div class="notice/content">
    <span class="label fill:blue margin-right:u2">NEW</span>
    <span class="font-size:body">Sample Notification</span>
  </div>

  <div class="notice/close">
    <span></span>
  </div>
</div>



{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="notice fill:red is-active">
  ...
</div>

<div class="notice fill:blue is-active">
  ...
</div>

<div class="notice fill:orange is-active">
  ...
</div>
...
```
{{% /codeblock %}}

### Alignment

Alignment can be modified with the `align` component.

<div class="notice justify-content:center margin-bottom:u2 is-active">
  <div class="notice/content">
    <span class="label -middle -white u-margin-right-1">NEW</span>
    Sample Notification
  </div>

  <div class="notice/close">
    <span></span>
  </div>
</div>

{{% codeblock key="language" definition="html" margin="top-tight" %}}
```html
<div class="notice justify-content:center is-active">
  ...
</div>
```
{{% /codeblock %}}

### Shapes

You can apply differently shaped corners to buttons with the `border` component.

<div class="notice border-radius:sharp is-active">
  <div class="notice/content">
    <span class="label fill:blue margin-right:u2">NEW</span>
    <span class="font-size:body">Sample Notification</span>
  </div>

  <div class="notice/close">
    <span></span>
  </div>
</div>

<div class="notice border-radius:round is-active">
  <div class="notice/content">
    <span class="label fill:blue margin-right:u2">NEW</span>
    <span class="font-size:body">Sample Notification</span>
  </div>

  <div class="notice/close">
    <span></span>
  </div>
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="notice border-radius:sharp is-active">
  ...
</div>
<div class="notice border-radius:round is-active">
  ...
</div>
```
{{% /codeblock %}}

### Local Variables

You can override styling using the following local variables.

{{% codeblock key="language" definition="css" margin="bottom" %}}
```css
--notice-fill: var(--primary-color);
```
{{% /codeblock %}}

### JS Settings

<table class="table width:100% ">
  <thead>
    <tr>
      <th>
        <strong>Setting</strong>
      </th>
      <th>
        <strong>Default</strong>
      </th>
      <th>
        <strong>Description</strong>
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td data-label="Setting">
        <code>element</code>
      </td>
      <td data-label="Default">
        <code>.notice</code>
      </td>
      <td data-label="Description">
        Define the element class name to initialize.
      </td>
    </tr>
  </tbody>
</table>
