+++
title = "Overflow"
date = "2018-04-11T09:16:45+12:00"
family = "Utility"
draft = false
description = "The overflow component manipulates the overflow visibility of a given element."
+++

### Basic Usage

Defined with `overflow`, you can apply basic or horizontal and vertical or overflow visibility modifiers. Responsive suffixes are available.

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<h3 class="overflow:visible">
	...
</h3>
<h3 class="overflow:hidden">
	...
</h3>
<h3 class="overflow-x:visible">
...
</h3>
<h3 class="overflow-y:visible">
...
</h3>
<h3 class="overflow-x@md:visible">
...
</h3>
<h3 class="overflow-y@lg:hidden">
...
</h3>
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
      <code>overflow</code>
    </td>
    <td data-label="Attributes">
      <code>:visible</code> <code>:hidden</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td>
      Set overflow visibility
    </td>
  </tr>
	<tr>
    <td data-label="Properties">
      <code>overflow-[x or y]</code>
    </td>
    <td data-label="Attributes">
      <code>:visible</code> <code>:hidden</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td>
      Set overflow visibility of horizontal and vertical
    </td>
  </tr>
</table>
