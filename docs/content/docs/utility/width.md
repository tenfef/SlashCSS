+++
title = "Width"
date = "2018-04-11T09:16:45+12:00"
family = "Utility"
draft = false
description = "The width component adds width to any object or container."
+++

### Basic Usage

Defind with `width`. There are 20 levels of unit based widths available.

```html
<div class="width:u1"></div>
<div class="width:u2"></div>
<div class="width:u3"></div>
<div class="width:u4"></div>
<div class="width:u5"></div>
<div class="width:u6"></div>
<div class="width:u7"></div>
<div class="width:u8"></div>
<div class="width:u9"></div>
<div class="width:u10"></div>
<div class="width:u11"></div>
<div class="width:u12"></div>
<div class="width:u13"></div>
<div class="width:u14"></div>
<div class="width:u15"></div>
<div class="width:u16"></div>
<div class="width:u17"></div>
<div class="width:u18"></div>
<div class="width:u19"></div>
<div class="width:u20"></div>
```

### Extra Modifiers

Percentage based widths and default settings are also available.

```html
<div class="width:10%"></div>
<div class="width:20%"></div>
<div class="width:30%"></div>
<div class="width:40%"></div>
<div class="width:50%"></div>
<div class="width:60%"></div>
<div class="width:70%"></div>
<div class="width:80%"></div>
<div class="width:90%"></div>
<div class="width:100%"></div>
<div class="width:auto"></div>
```

### Responsive Margin

To apply responsive widths add responsive suffixes

```html
<div class="width:u8 width@sm:u10">
  ...
</div>
```

### Local Variables

You can override this component using the following local variables.

```css
$widths: 20 !default;
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
      <code>width</code>
    </td>
    <td data-label="Attributes">
      <code>:u1</code> ... <code>:u20</code><br>
      <code>:10%</code> ... <code>:100%</code><br />
      <code>:auto</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td>
      Set width
    </td>
  </tr>
</table>
