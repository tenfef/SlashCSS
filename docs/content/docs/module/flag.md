+++
title = "Flag"
date = "2018-04-11T09:16:45+12:00"
family = "Module"
draft = false
description = "The markup component formats general paragraph and heading elements for readability."
+++

### Flag Object

The flag object is similar to Nicole Sullivan's media object, however it is flexbox based and not limited to just image and body. You can include as many child items as you like.

<div class="flag flag-gutter:u4 margin-bottom:u4">
  <div class="flag/item">
    <img src="/assets/images/jin.jpg" class="media elevate border border-width:3px border-color:white media-size:md border-radius:round" alt="Jin Su Park">
  </div>
  <div class="flag/item font-height:1">
    <h6 class="margin:u0">Jin Su Park</h6>
    <p>@slashcss</p>
  </div>
</div>

```html
<div class="flag flag-gutter:u4">
  <div class="flag/item">
    Image Left
  </div>
  <div class="flag/item">
    Text Right
  </div>
</div>
```

### Local Variables

You can override this component using the following local variables.

```css
$flag-gutters: 5 !default;
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
      <code>flag</code>
    </td>
    <td data-label="Attributes">

    </td>
    <td data-label="Responsive">
      No
    </td>
    <td>
      Apply flag component
    </td>
  </tr>
  <tr>
    <td data-label="Properties">
      <code>flag-gutter</code>
    </td>
    <td data-label="Attributes">
      <code>:u2</code> <code>:u4</code> <code>:u6</code> <code>:u8</code> <code>:u10</code>
    </td>
    <td data-label="Responsive">
      No
    </td>
    <td>
      Define spacing between flag item
    </td>
  </tr>
</table>
