+++
title = "List"
date = "2018-04-11T09:16:45+12:00"
draft = false
description = "The list module is used to present any list of content horizontally or vertically."
+++

##### Basic Usage

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

##### Gutter Spacing

You can use the standard spacing modifiers to control the spread between list items. You can make your list run horizontally with the `list:horizontal` modifier.

<ul class="list list-gutter:1 list:horizontal margin-bottom:2" style="margin-left: 0">
  <li class="list/item">
    <div class="image border:sharp image-shape:square image-size:2 fill:primary">
    </div>
  </li>
  <li class="list/item">
    <div class="image border:sharp image-shape:square image-size:2 fill:primary">
    </div>
  </li>
  <li class="list/item">
    <div class="image border:sharp image-shape:square image-size:2 fill:primary">
    </div>
  </li>
</ul>

<ul class="list list-gutter:2 list:horizontal margin-bottom:2" style="margin-left: 0">
  <li class="list/item">
    <div class="image border:sharp image-shape:square image-size:2 fill:primary">
    </div>
  </li>
  <li class="list/item">
    <div class="image border:sharp image-shape:square image-size:2 fill:primary">
    </div>
  </li>
  <li class="list/item">
    <div class="image border:sharp image-shape:square image-size:2 fill:primary">
    </div>
  </li>
</ul>

<ul class="list list-gutter:3 list:horizontal margin-bottom:2" style="margin-left: 0">
  <li class="list/item">
    <div class="image border:sharp image-shape:square image-size:2 fill:primary">
    </div>
  </li>
  <li class="list/item">
    <div class="image border:sharp image-shape:square image-size:2 fill:primary">
    </div>
  </li>
  <li class="list/item">
    <div class="image border:sharp image-shape:square image-size:2 fill:primary">
    </div>
  </li>
</ul>

<ul class="list list-gutter:4 list:horizontal margin-bottom:2" style="margin-left: 0">
  <li class="list/item">
    <div class="image border:sharp image-shape:square image-size:2 fill:primary">
    </div>
  </li>
  <li class="list/item">
    <div class="image border:sharp image-shape:square image-size:2 fill:primary">
    </div>
  </li>
  <li class="list/item">
    <div class="image border:sharp image-shape:square image-size:2 fill:primary">
    </div>
  </li>
</ul>

<ul class="list list-gutter:5 list:horizontal margin-bottom:2" style="margin-left: 0">
  <li class="list/item">
    <div class="image border:sharp image-shape:square image-size:2 fill:primary">
    </div>
  </li>
  <li class="list/item">
    <div class="image border:sharp image-shape:square image-size:2 fill:primary">
    </div>
  </li>
  <li class="list/item">
    <div class="image border:sharp image-shape:square image-size:2 fill:primary">
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
<ul class="list list-gutter:2">
  <li class="list/item">...</li>
  <li class="list/item">...</li>
  <li class="list/item">...</li>
  <li class="list/item">...</li>
</ul>
<ul class="list list-gutter:3">
  <li class="list/item">...</li>
  <li class="list/item">...</li>
  <li class="list/item">...</li>
  <li class="list/item">...</li>
</ul>
<ul class="list list-gutter:4">
  <li class="list/item">...</li>
  <li class="list/item">...</li>
  <li class="list/item">...</li>
  <li class="list/item">...</li>
</ul>
<ul class="list list-gutter:5">
  <li class="list/item">...</li>
  <li class="list/item">...</li>
  <li class="list/item">...</li>
  <li class="list/item">...</li>
</ul>
```
{{% /codeblock %}}

##### Settings

The following settings are available.

<table class="table table:fluid table:pile">
  <thead>
    <tr>
      <th>
        Properties
      </th>
      <th>
        Attributes
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
      <code>list</code>
    </td>
    <td data-label="Attributes">
      <code>:horizontal</code>
    </td>
    <td data-label="Responsive">
      No
    </td>
    <td class="row:reverse">
      Enable horizontal direction
    </td>
  </tr>
  <tr>
    <td data-label="Properties">
      <code>list-gutter</code>
    </td>
    <td data-label="Attributes">
      <code>:1</code>...<code>:5</code>
    </td>
    <td data-label="Responsive">
      No
    </td>
    <td class="row:reverse">
      Gutter width between list items
    </td>
  </tr>
</table>
