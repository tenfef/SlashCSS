+++
title = "Height"
date = "2018-04-11T09:16:45+12:00"
family = "Utility"
draft = false
description = "The height component adds height to any object or container."
+++

### Basic Usage

Defind with `height`. There are 20 levels of unit based heights available.

```html
<div class="height:u1"></div>
<div class="height:u2"></div>
<div class="height:u3"></div>
<div class="height:u4"></div>
<div class="height:u5"></div>
<div class="height:u6"></div>
<div class="height:u7"></div>
<div class="height:u8"></div>
<div class="height:u9"></div>
<div class="height:u10"></div>
<div class="height:u11"></div>
<div class="height:u12"></div>
<div class="height:u13"></div>
<div class="height:u14"></div>
<div class="height:u15"></div>
<div class="height:u16"></div>
<div class="height:u17"></div>
<div class="height:u18"></div>
<div class="height:u19"></div>
<div class="height:u20"></div>
```

### Extra Modifiers

Full heights and default settings are also available.

```html
<div class="height:100%"></div>
<div class="height:auto"></div>
```

### Responsive Margin

To apply responsive heights add responsive suffixes

```html
<div class="height:u8 height@sm:u10">
  ...
</div>
```

### Local Variables

You can override this component using the following local variables.

```css
$heights: 20 !default;
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
      <code>height</code>
    </td>
    <td data-label="Attributes">
      <code>:u1</code> ... <code>:u20</code><br>
      <code>:100%</code> <code>:auto</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td>
      Set height
    </td>
  </tr>
</table>
