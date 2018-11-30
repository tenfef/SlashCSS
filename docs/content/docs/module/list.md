+++
title = "List"
date = "2018-04-11T09:16:45+12:00"
family = "Module"
draft = false
description = "The list module is used to present any list of content horizontally or vertically."
+++

### Basic Usage

The list module `list` is useful for any type of list content that runs horizontally and vertically.

```html
<ul class="list">
  <li class="list/item">List Item</li>
  <li class="list/item">List Item</li>
  <li class="list/item">List Item</li>
</ul>

<ul class="list:inline">
  <li class="list/item">List Item</li>
  <li class="list/item">List Item</li>
  <li class="list/item">List Item</li>
</ul>
```

### List Gutters

You can use the `list-gutter` property to control the gutter between list items. You can make your list run horizontally with the `list:inline` modifier.

<div class="row">
  <div class="column">

    <ul class="list distribute-y:u2 margin:u0 margin-bottom:u2">
      <li class="list/item">
        <div class="padding:u4 border-radius fill:blue">
        </div>
      </li>
      <li class="list/item">
        <div class="padding:u4 border-radius fill:blue">
        </div>
      </li>
      <li class="list/item">
        <div class="padding:u4 border-radius fill:blue">
        </div>
      </li>
    </ul>

  </div>
  <div class="column">

    <ul class="list list-gutter:u4 margin:u0 margin-bottom:u2">
      <li class="list/item">
        <div class="padding:u4 border-radius fill:blue">
        </div>
      </li>
      <li class="list/item">
        <div class="padding:u4 border-radius fill:blue">
        </div>
      </li>
      <li class="list/item">
        <div class="padding:u4 border-radius fill:blue">
        </div>
      </li>
    </ul>

  </div>
  <div class="column">

    <ul class="list list-gutter:u6 margin:u0 margin-bottom:u2">
      <li class="list/item">
        <div class="padding:u4 border-radius fill:blue">
        </div>
      </li>
      <li class="list/item">
        <div class="padding:u4 border-radius fill:blue">
        </div>
      </li>
      <li class="list/item">
        <div class="padding:u4 border-radius fill:blue">
        </div>
      </li>
    </ul>

  </div>
  <div class="column">

    <ul class="list list-gutter:u8 margin:u0 margin-bottom:u2">
      <li class="list/item">
        <div class="padding:u4 border-radius fill:blue">
        </div>
      </li>
      <li class="list/item">
        <div class="padding:u4 border-radius fill:blue">
        </div>
      </li>
      <li class="list/item">
        <div class="padding:u4 border-radius fill:blue">
        </div>
      </li>
    </ul>

  </div>
  <div class="column">

    <ul class="list list-gutter:u10 margin:u0 margin-bottom:u2">
      <li class="list/item">
        <div class="padding:u4 border-radius fill:blue">
        </div>
      </li>
      <li class="list/item">
        <div class="padding:u4 border-radius fill:blue">
        </div>
      </li>
      <li class="list/item">
        <div class="padding:u4 border-radius fill:blue">
        </div>
      </li>
    </ul>

  </div>
</div>

```html
<ul class="list distribute-y:u2">
  <li class="list/item">...</li>
  <li class="list/item">...</li>
  <li class="list/item">...</li>
</ul>
<ul class="list list-gutter:u4">
  <li class="list/item">...</li>
  <li class="list/item">...</li>
  <li class="list/item">...</li>
</ul>
<ul class="list list-gutter:u6">
  <li class="list/item">...</li>
  <li class="list/item">...</li>
  <li class="list/item">...</li>
</ul>
<ul class="list list-gutter:u8">
  <li class="list/item">...</li>
  <li class="list/item">...</li>
  <li class="list/item">...</li>
</ul>
<ul class="list list-gutter:u10">
  <li class="list/item">...</li>
  <li class="list/item">...</li>
  <li class="list/item">...</li>
</ul>
```

### Local Variables

You can override this component using the following local variables.

```css
$list-gutters: 5 !default;
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
      <code>list-gutter</code>
    </td>
    <td data-label="Attributes">
      <code>:u2</code> <code>:u4</code> <code>:u6</code> <code>:u8</code> <code>:u10</code>
    </td>
    <td data-label="Responsive">
      No
    </td>
    <td>
      Set gutter width
    </td>
  </tr>
</table>
