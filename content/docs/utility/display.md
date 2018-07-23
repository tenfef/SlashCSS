+++
title = "Display"
date = "2018-04-11T09:16:45+12:00"
draft = false
description = "The display component controls the display property of your element."
+++

### Basic Usage

Defined with the `display` property, modify your display behavior of an element. You can also apply responsive suffixes.

{{% codeblock key="language" definition="html" margin="bottom" %}}
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
<div class="display:flex">
  Flex
</div>
<div class="display:inline-flex">
  Flex
</div>
<div class="display:grid">
  Grid
</div>
<div class="display:inline-grid">
  Inline Grid
</div>
```
{{% /codeblock %}}

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
      <code>:none</code><br>
      <code>:inline-block</code><br>
      <code>:flex</code><br>
      <code>:inline-flex</code><br>
      <code>:grid</code><br>
      <code>:inline-grid</code><br>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td class="row:reverse">
      Set display type
    </td>
  </tr>
</table>
<p class="margin-top:2 font-size:tiny color:orange">
  &#42; These properties have a default values set when used without modifiers.
</p>
