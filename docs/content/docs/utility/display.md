+++
title = "Display"
date = "2018-04-11T09:16:45+12:00"
family = "Utility"
draft = false
description = "The display component controls the display property of your element."
+++

### Basic Usage

Defined with the `display` property, modify your display behavior of an element. You can also apply responsive suffixes.

```html
<div class="display">
  Block
</div>
<div class="display:none">
  None
</div>
<div class="display:inline-block">
  Inline Block
</div>
<div class="flex">
  Flex
</div>
<div class="display:inline-flex">
  Inline Flex
</div>
<div class="display:grid">
  Grid
</div>
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
      <code>display</code><span class="color:orange">&#42;</span>
    </td>
    <td data-label="Attributes">
      <code class="margin:u0">:none</code><br>
      <code class="margin:u0">:inline-block</code><br>
      <code class="margin:u0">:flex</code><br>
      <code class="margin:u0">:inline-flex</code><br>
      <code class="margin:u0">:grid</code><br>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td>
      Set display type
    </td>
  </tr>
</table>
<p class="margin-top:2 font-size:tiny color:orange">
  &#42; These properties have a default values set when used without modifiers.
</p>
