+++
title = "Position"
date = "2018-04-11T09:16:45+12:00"
family = "Utility"
draft = false
description = "The position component manipulates the positin property of a given element."
+++

### Basic Usage

Defined with `position`. Responsive suffixes are available for this component.

```html
<h3 class="position">
	...
</h3>
<h3 class="position:absolute">
	...
</h3>
<h3 class="position:fixed">
	...
</h3>
<h3 class="position:relative">
...
</h3>
```

### Postioning Element

You can position elements to the edge inside containers with the positional suffixes.

```html
<h3 class="position-top">
	...
</h3>
<h3 class="position-right">
	...
</h3>
<h3 class="position-bottom">
	...
</h3>
<h3 class="position-left">
	...
</h3>
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
      <code>position</code><span class="color:orange">&#42;</span>
    </td>
    <td data-label="Attributes">
      <code>:absolute</code> <code>:fixed</code> <code>:relative</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td>
      Set position property
    </td>
  </tr>
	<tr>
    <td data-label="Properties">
      <code>position-[direction]</code>
    </td>
    <td data-label="Attributes">

    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td>
      Set edge position
    </td>
  </tr>
</table>

<p class="margin-top:2 font-size:tiny color:orange">
  &#42; These properties have a default values set when used without modifiers.
</p>
