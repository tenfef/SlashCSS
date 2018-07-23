+++
title = "List"
date = "2018-04-11T09:16:45+12:00"
draft = false
description = "The list module is used to present any list of content horizontally or vertically."
+++

### Basic Usage

The list module `list` is useful for any type of list content that runs horizontally and vertically.

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<ul class="list">
  <li class="list/item">List Item</li>
  <li class="list/item">List Item</li>
  <li class="list/item">List Item</li>
</ul>
```
{{% /codeblock %}}

### List Gutters

You can use the `list-gutter` property to control the gutter between list items. You can make your list run horizontally with the `list-direction:right` modifier.

<ul class="list list-gutter:1 margin-bottom:2">
  <li class="list/item">
    <div class="padding:2 border-style:radius fill:red">
    </div>
  </li>
  <li class="list/item">
    <div class="padding:2 border-style:radius fill:red">
    </div>
  </li>
  <li class="list/item">
    <div class="padding:2 border-style:radius fill:red">
    </div>
  </li>
</ul>

<ul class="list list-gutter:2 list-direction:right margin-bottom:2">
  <li class="list/item">
    <div class="padding:2 border-style:radius fill:blue">
    </div>
  </li>
  <li class="list/item">
    <div class="padding:2 border-style:radius fill:blue">
    </div>
  </li>
  <li class="list/item">
    <div class="padding:2 border-style:radius fill:blue">
    </div>
  </li>
</ul>

<ul class="list list-gutter:3 list-direction:right margin-bottom:2">
  <li class="list/item">
    <div class="padding:2 border-style:radius fill:blue">
    </div>
  </li>
  <li class="list/item">
    <div class="padding:2 border-style:radius fill:blue">
    </div>
  </li>
  <li class="list/item">
    <div class="padding:2 border-style:radius fill:blue">
    </div>
  </li>
</ul>

<ul class="list list-gutter:4 list-direction:right margin-bottom:2">
  <li class="list/item">
    <div class="padding:2 border-style:radius fill:blue">
    </div>
  </li>
  <li class="list/item">
    <div class="padding:2 border-style:radius fill:blue">
    </div>
  </li>
  <li class="list/item">
    <div class="padding:2 border-style:radius fill:blue">
    </div>
  </li>
</ul>

<ul class="list list-gutter:5 list-direction:right margin-bottom:2">
  <li class="list/item">
    <div class="padding:2 border-style:radius fill:blue">
    </div>
  </li>
  <li class="list/item">
    <div class="padding:2 border-style:radius fill:blue">
    </div>
  </li>
  <li class="list/item">
    <div class="padding:2 border-style:radius fill:blue">
    </div>
  </li>
</ul>


{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<ul class="list list-gutter:1">
  <li class="list/item">...</li>
  <li class="list/item">...</li>
  <li class="list/item">...</li>
  <li class="list/item">...</li>
</ul>
<ul class="list list-direction:right list-gutter:2">
  <li class="list/item">...</li>
  <li class="list/item">...</li>
  <li class="list/item">...</li>
  <li class="list/item">...</li>
</ul>
<ul class="list list-direction:right list-gutter:3">
  <li class="list/item">...</li>
  <li class="list/item">...</li>
  <li class="list/item">...</li>
  <li class="list/item">...</li>
</ul>
<ul class="list list-direction:right list-gutter:4">
  <li class="list/item">...</li>
  <li class="list/item">...</li>
  <li class="list/item">...</li>
  <li class="list/item">...</li>
</ul>
<ul class="list list-direction:right list-gutter:5">
  <li class="list/item">...</li>
  <li class="list/item">...</li>
  <li class="list/item">...</li>
  <li class="list/item">...</li>
</ul>
```
{{% /codeblock %}}

### Local Variables

You can override styling using the following local variables.

{{% codeblock key="language" definition="css" margin="bottom" %}}
```css
$list-gutters: 5 !default;
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
      <code>list-gutter</code>
    </td>
    <td data-label="Attributes">
      <code>:1</code> ... <code>:5</code>
    </td>
    <td data-label="Responsive">
      No
    </td>
    <td class="row:reverse">
      Set gutter width
    </td>
  </tr>
</table>
