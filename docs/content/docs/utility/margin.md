+++
title = "Margin"
date = "2018-04-11T09:16:45+12:00"
family = "Utility"
draft = false
description = "The margin component adds margin to any object or container."
+++

### Basic Usage

Defind with `margin`. There are 8 levels of margin which step up in increments of 2 unit.

```html
<div class="margin:u0"></div>
<div class="margin:u2"></div>
<div class="margin:u4"></div>
<div class="margin:u6"></div>
<div class="margin:u8"></div>
<div class="margin:u10"></div>
<div class="margin:u12"></div>
<div class="margin:u14"></div>
```

### Directional Margin

Margin can be applied to `top` `right` `bottom` `left`.

```html
<div class="margin-top:u0"></div>
<div class="margin-right:u2"></div>
<div class="margin-bottom:u4"></div>
<div class="margin-left:u6"></div>
```

### Responsive Margin

To apply responsive margins add responsive suffixes

```html
<div class="margin:u0 margin@sm:u2">
  ...
</div>
```

### Local Variables

You can override this component using the following local variables.

```css
$margins: 15 !default;
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
      <code>margin</code>
    </td>
    <td data-label="Attributes">
      <code class="margin:u0">:auto</code><br />
      <code class="margin:u0">:u0</code><br />
      <code class="margin:u0">:u2</code><br />
      <code class="margin:u0">:u4</code><br />
      <code class="margin:u0">:u6</code><br />
      <code class="margin:u0">:u8</code><br />
      <code class="margin:u0">:u10</code><br />
      <code class="margin:u0">:u12</code><br />
      <code class="margin:u0">:u14</code><br />
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td>
      Set unit based margin
    </td>
  </tr>
  <tr>
    <td data-label="Properties">
      <code class="margin:u0">margin-[direction]</code><br />
        </td>
    <td data-label="Attributes">
      <code class="margin:u0">:auto</code><br />
      <code class="margin:u0">:u0</code><br />
      <code class="margin:u0">:u2</code><br />
      <code class="margin:u0">:u4</code><br />
      <code class="margin:u0">:u6</code><br />
      <code class="margin:u0">:u8</code><br />
      <code class="margin:u0">:u10</code><br />
      <code class="margin:u0">:u12</code><br />
      <code>:u14</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td>
      Set directional margin
    </td>
  </tr>
  <tr>
    <td data-label="Properties">
      <code class="margin:u0">margin-[top bottom]</code>
    </td>
    <td data-label="Attributes">
      <code class="margin:u0">:5vh</code><br />
      <code class="margin:u0">:6vh</code><br />
      <code class="margin:u0">:7vh</code><br />
      <code class="margin:u0">:8vh</code><br />
      <code class="margin:u0">:9vh</code><br />
      <code class="margin:u0">:10vh</code><br />
      <code class="margin:u0">:11vh</code><br />
      <code class="margin:u0">:12vh</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td>
      Set viewport based directional margin
    </td>
  </tr>
</table>
