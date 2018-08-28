+++
title = "Flex"
date = "2018-04-11T09:16:45+12:00"
family = "Layout"
draft = false
description = "The flex component provides flex based layout options."
+++

### Basic Usage

The flex component applies flex display property to an element.

```html
<div class="flex">
  ...
</div>
<div class="flex:inline">
  ...
</div>
```

### Flex Grow Options

The flex component also provides grow options.

```html
<div class="flex:1">
  ...
</div>
<div class="flex:none">
  ...
</div>
```

### Flex Directions

The flex direction property can be set with the following modifiers.

```html
<div class="flex-direction:row">
  ...
</div>
<div class="flex-direction:column">
  ...
</div>
<div class="flex-direction:reverse">
  ...
</div>
```

### Flex Wrap

The flex wrap property can be set with the following modifiers.

```html
<div class="flex-wrap">
  ...
</div>
<div class="flex-wrap:nowrap">
  ...
</div>
```

### Flex Order

The order property can be set with the following modifiers.

```html
<div class="flex-order:1">
  ...
</div>
<div class="flex-order:2">
  ...
</div>
<div class="flex-order:12">
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
      <code>flex</code>
    </td>
    <td data-label="Attributes">
      <code>:inline</code> <code>:1</code> <code>:none</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td class="row:reverse">
      Apply flex display and grow properties
    </td>
  </tr>
  <tr>
    <td data-label="Properties">
      <code>flex-direction</code>
    </td>
    <td data-label="Attributes">
      <code>:row</code> <code>:column</code> <code>:reverse</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td class="row:reverse">
      Apply flex direction properties
    </td>
  </tr>
  <tr>
    <td data-label="Properties">
      <code>flex-wrap</code>
    </td>
    <td data-label="Attributes">
      <code>:nowrwap</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td class="row:reverse">
      Apply flex wrap properties
    </td>
  </tr>
  <tr>
    <td data-label="Properties">
      <code>flex-order</code>
    </td>
    <td data-label="Attributes">
      <code>:1</code> ... <code>:12</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td class="row:reverse">
      Apply order properties
    </td>
  </tr>
</table>
