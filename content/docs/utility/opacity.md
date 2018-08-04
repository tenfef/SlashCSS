+++
title = "Opacity"
date = "2018-04-11T09:16:45+12:00"
family = "Utility"
draft = false
description = "The opacity component manipulates the opacity property of a given element."
+++

### Basic Usage

Defined with `opacity`, there are 9 fade options available.

<h3 class="margin:0 opacity:1">Opacity 1</h3>
<h3 class="margin:0 opacity:2">Opacity 2</h3>
<h3 class="margin:0 opacity:3">Opacity 3</h3>
<h3 class="margin:0 opacity:4">Opacity 4</h3>
<h3 class="margin:0 opacity:5">Opacity 5</h3>
<h3 class="margin:0 opacity:6">Opacity 6</h3>
<h3 class="margin:0 opacity:7">Opacity 7</h3>
<h3 class="margin:0 opacity:8">Opacity 8</h3>
<h3 class="margin:0 opacity:8">Opacity 9</h3>
<h3 class="margin:0 margin-bottom:u6 opacity:10">Opacity 10</h3>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<h3 class="opacity:0">Opacity 0</h3>
<h3 class="opacity:1">Opacity 1</h3>
<h3 class="opacity:2">Opacity 2</h3>
<h3 class="opacity:3">Opacity 3</h3>
<h3 class="opacity:4">Opacity 4</h3>
<h3 class="opacity:5">Opacity 5</h3>
<h3 class="opacity:6">Opacity 6</h3>
<h3 class="opacity:7">Opacity 7</h3>
<h3 class="opacity:8">Opacity 8</h3>
<h3 class="opacity:9">Opacity 9</h3>
<h3 class="opacity:10">Opacity 10</h3>
```
{{% /codeblock %}}

### Opacity Value Chart

{{% codeblock key="language" definition="css" margin="bottom" %}}
```css
.opacity {
	&-0 {
		opacity: 0;
	}
	&-1 {
		opacity: .1;
	}
	&-2 {
		opacity: .2;
	}
	&-3 {
		opacity: .3;
	}
	&-4 {
		opacity: .4;
	}
	&-5 {
		opacity: .5;
	}
	&-6 {
		opacity: .6;
	}
	&-7 {
		opacity: .7;
	}
	&-8 {
		opacity: .8;
	}
	&-9 {
		opacity: .9;
	}
}
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
      <code>opacity</code>
    </td>
    <td data-label="Attributes">
      <code>:1</code> ... <code>:10</code>
    </td>
    <td data-label="Responsive">
      No
    </td>
    <td class="row:reverse">
      Set opacity level
    </td>
  </tr>
</table>
