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
    <span class="pill fill:black">NEW</span>
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
    <span class="pill fill:orange">NEW</span>
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

You can change the background color with the `fill` component.

<div class="notice fill:blue margin-bottom:u2 is-active">
  <div class="notice/content">
    <span class="pill fill:orange">NEW</span>
    <span class="font-size:body">Sample Notification</span>
  </div>

  <div class="notice/close">
    <span></span>
  </div>
</div>

<div class="notice fill:orange margin-bottom:u2 is-active">
  <div class="notice/content">
    <span class="pill fill:white color:orange">NEW</span>
    <span class="font-size:body">Sample Notification</span>
  </div>

  <div class="notice/close">
    <span></span>
  </div>
</div>

<div class="notice fill:violet margin-bottom:u2 is-active">
  <div class="notice/content">
    <span class="pill fill:navy">NEW</span>
    <span class="font-size:body">Sample Notification</span>
  </div>

  <div class="notice/close">
    <span></span>
  </div>
</div>

```html
<div class="notice fill:blue is-active">
  ...
</div>

<div class="notice fill:orange is-active">
  ...
</div>

<div class="notice fill:violet is-active">
  ...
</div>
```

### Alignment

Alignment can be modified with the `justify` component.

<div class="notice justify-content:center is-active">
  <div class="notice/content">
    <span class="pill fill:orange">NEW</span>
    Sample Notification
  </div>
  <div class="notice/close">
    <span></span>
  </div>
</div>

```html
<div class="notice justify-content:center is-active">
  ...
</div>
```

### Shapes

You can apply differently shaped corners to buttons with the `border` component.

<div class="notice border-radius:sharp is-active">
  <div class="notice/content">
    <span class="pill fill:red">NEW</span>
    <span class="font-size:body">Sample Notification</span>
  </div>

  <div class="notice/close">
    <span></span>
  </div>
</div>

<div class="notice border-radius:round is-active">
  <div class="notice/content">
    <span class="pill fill:red">NEW</span>
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


### JS Settings

<table class="table width:100% table:pile table@sm:unpile">
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
