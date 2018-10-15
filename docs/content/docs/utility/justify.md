+++
title = "Justify"
date = "2018-04-11T09:16:45+12:00"
family = "Utility"
draft = false
description = "The height component adds height to any object or container."
+++

### Basic Usage

Justify component justifies text or deals with flexbox base justification of content.

```html
<div class="justify">
  ...
</div>
<div class="justify-content:start">
  ...
</div>
<div class="justify-content:end">
  ...
</div>
<div class="justify-content:center">
  ...
</div>
<div class="justify-content:between">
  ...
</div>
<div class="justify-content:around">
  ...
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
      <code>justify</code>
    </td>
    <td data-label="Attributes">

    </td>
    <td data-label="Responsive">
      No
    </td>
    <td>
      Sets text alignment to justify
    </td>
  </tr>
  <tr>
    <td data-label="Properties">
      <code>justify-content</code>
    </td>
    <td data-label="Attributes">
      <code class="margin:u0">:start</code><br>
      <code class="margin:u0">:end</code><br>
      <code class="margin:u0">:center</code><br>
      <code class="margin:u0">:between</code><br>
      <code class="margin:u0">:around</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td>
      Set flex justification
    </td>
  </tr>
</table>
