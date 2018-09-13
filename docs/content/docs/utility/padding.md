+++
title = "Padding"
date = "2018-04-11T09:16:45+12:00"
family = "Utility"
draft = false
description = "The padding component adds padding to any object or container."
+++

### Basic Usage

Defind with `padding`. There are 16 levels of padding which are based on the standard unit chart.

```html
<div class="padding:u0"></div>
<div class="padding:u2"></div>
<div class="padding:u4"></div>
<div class="padding:u6"></div>
<div class="padding:u8"></div>
<div class="padding:u10"></div>
<div class="padding:u12"></div>
<div class="padding:u14"></div>
```

### Directional Padding

Padding can be applied to `top` `right` `bottom` `left`.

```html
<div class="padding-top:u0"></div>
<div class="padding-right:u2"></div>
<div class="padding-bottom:u4"></div>
<div class="padding-left:u6"></div>
```

### Responsive Padding

To apply responsive margins add responsive suffixes

```html
<div class="padding:u0 padding@sm:u2">
  ...
</div>
```

### Viewport Padding

The padding component also supports viewport height based paddings.

```html
<div class="padding-top:10vh">
  ...
</div>
<div class="padding-bottom@md:6vh">
  ...
</div>
<div class="padding-y@md:5vh">
  ...
</div>
```

### Horizontal & Vertical Padding

To apply padding in both left and right or top and bottom directions use x and y respectively.

```html
<div class="padding-x:u10">
  ...
</div>
<div class="padding-y@md:u6">
  ...
</div>
```

### Local Variables

You can override this component using the following local variables.

```css
$paddings: 7 !default;
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
      <code>padding</code>
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
      <code class="margin:u0">:u14</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td>
      Set unit based padding
    </td>
  </tr>
  <tr>
    <td data-label="Properties">
      <code class="margin:u0">padding-[direction]</code><br />
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
      <code class="margin:u0">:u14</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td>
      Set directional padding
    </td>
  </tr>
  <tr>
    <td data-label="Properties">
      <code class="margin:u0">padding-[top bottom]</code>
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
      Set viewport based directional padding
    </td>
  </tr>
</table>
