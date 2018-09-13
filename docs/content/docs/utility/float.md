+++
title = "Float"
date = "2018-04-11T09:16:45+12:00"
family = "Utility"
draft = false
description = "The float component forces float of any given element."
+++

### Basic Usage

Defined with `float` and direction.

<div class="row margin-bottom:u4">
  <div class="column:12">
    <img src="https://placeimg.com/200/200/people" class="media media-size:xl float:left">
  </div>
</div>
<div class="row margin-bottom:u4">
  <div class="column:12">
    <img src="https://placeimg.com/200/200/people" class="media media-size:xl float:right">
  </div>
</div>
<div class="row margin-bottom:u4">
  <div class="column:12">
    <img src="https://placeimg.com/200/200/people" class="media media-size:xl float:none">
  </div>
</div>

```html
<div class="float:left">
  ...
</div>
<div class="float:right">
  ...
</div>
<div class="float:none">
  ...
</div>
```

### Responsive Floats

You can assign responsive floats by adding responsive suffixes.

```html
<div class="float@sm:left">
  ...
</div>
<div class="float@md:right">
  ...
</div>
<div class="float@lg:none">
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
      <code>float</code>
    </td>
    <td data-label="Attributes">
      <code>:none</code> <code>:left</code> <code>:right</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td>
      Define float
    </td>
  </tr>
</table>
