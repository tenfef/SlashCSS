+++
title = "Max"
date = "2018-04-11T09:16:45+12:00"
family = "Utility"
draft = false
description = "The max component provides max width or max height properties."
+++

### Basic Usage

Defind with `max-width` and `max-height`.

```html
<div class="max-width:100px"></div>
<div class="max-width:200px"></div>
<div class="max-width:300px"></div>
<div class="max-width:400px"></div>
<div class="max-width:500px"></div>
<div class="max-width:600px"></div>
<div class="max-width:700px"></div>
<div class="max-width:800px"></div>
<div class="max-width:900px"></div>
<div class="max-width:1000px"></div>

<div class="max-height:100px"></div>
<div class="max-height:200px"></div>
<div class="max-height:300px"></div>
<div class="max-height:400px"></div>
<div class="max-height:500px"></div>
<div class="max-height:600px"></div>
<div class="max-height:700px"></div>
<div class="max-height:800px"></div>
<div class="max-height:900px"></div>
<div class="max-height:1000px"></div>
```

### Fluid Modifiers

Widths and heights can be fluid.

```html
<div class="max-width:100%"></div>
<div class="max-height:100%"></div>
```

### Responsive Properties

To apply responsiveness add media query suffixes

```html
<div class="max-width@md:500px"></div>
<div class="max-width@lg:400px"></div>
```

### Local Variables

You can override this component using the following local variables.

```css
$max-levels: 10 !default;
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
      <code>max-width</code>
    </td>
    <td data-label="Attributes">
      <code class="margin:u0">:100px</code><br />
      <code class="margin:u0">:200px</code><br />
      <code class="margin:u0">:300px</code><br />
      <code class="margin:u0">:400px</code><br />
      <code class="margin:u0">:500px</code><br />
      <code class="margin:u0">:600px</code><br />
      <code class="margin:u0">:700px</code><br />
      <code class="margin:u0">:800px</code><br />
      <code class="margin:u0">:900px</code><br />
      <code class="margin:u0">:1000px</code><br />
      <code class="margin:u0">:100%</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td class="row:reverse">
      Set max width
    </td>
  </tr>
  <tr>
    <td data-label="Properties">
      <code>max-height</code>
    </td>
    <td data-label="Attributes">
      <td data-label="Attributes">
        <code class="margin:u0">:100px</code><br />
        <code class="margin:u0">:200px</code><br />
        <code class="margin:u0">:300px</code><br />
        <code class="margin:u0">:400px</code><br />
        <code class="margin:u0">:500px</code><br />
        <code class="margin:u0">:600px</code><br />
        <code class="margin:u0">:700px</code><br />
        <code class="margin:u0">:800px</code><br />
        <code class="margin:u0">:900px</code><br />
        <code class="margin:u0">:1000px</code><br />
        <code class="margin:u0">:100%</code>
      </td>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td class="row:reverse">
      Set max height
    </td>
  </tr>
</table>
