+++
title = "Float"
date = "2018-04-11T09:16:45+12:00"
family = "Utility"
draft = false
description = "The float component forces float of any given element."
+++

### Basic Usage

Defined with `float` and direction.

<div class="row margin-bottom:u2">
  <div class="column:12">
    <div class="width:10 height:10 float:left">
      <img src="https://placeimg.com/500/500/people">
    </div>
  </div>
</div>
<div class="row margin-bottom:u2">
  <div class="column:12">
    <div class="width:10 height:10 float:right">
      <img src="https://placeimg.com/500/500/people">
    </div>
  </div>
</div>
<div class="row margin-bottom:u2">
  <div class="column:12">
    <div class="width:10 height:10 float:none">
      <img src="https://placeimg.com/500/500/people">
    </div>
  </div>
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
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
{{% /codeblock %}}

### Responsive Floats

You can assign responsive floats by adding responsive suffixes.

{{% codeblock key="language" definition="html" margin="bottom" %}}
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
      <code>float</code>
    </td>
    <td data-label="Attributes">
      <code>:none</code> <code>:left</code> <code>:right</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td class="row:reverse">
      Define float
    </td>
  </tr>
</table>
