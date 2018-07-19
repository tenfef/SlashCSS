+++
title = "Flex"
date = "2018-04-11T09:16:45+12:00"
draft = false
description = "The flex component provide flexbox properties"
+++

##### Basic Usage

Defined with `flex` can accept `:1` or `:none` modifiers.

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="flex:1">
  ...
</div>
<div class="flex:none">
  ...
</div>
```
{{% /codeblock %}}



##### Flex Direction

Defined with `flex-direction` can accept `:row`, `:column` or `reverse`. Responsive suffixes are also available.

{{% codeblock key="language" definition="html" margin="bottom" %}}
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
{{% /codeblock %}}

##### Flex Wrap

You can define the `flex-wrap` to enable or disable flexible content wrapping.

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="flex-wrap">
  ...
</div>
...
<div class="flex-wrap:nowrap">
  ...
</div>
```
{{% /codeblock %}}

##### Flex Order

You can define the `flex-order` to reorder your flex columns. Responsive suffixes are also available.

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="flex-order:1">
  ...
</div>
...
<div class="flex-order:12">
  ...
</div>
```
{{% /codeblock %}}

##### Options

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
      <code>:1</code> <code>:none</code>
    </td>
    <td data-label="Responsive">
      No
    </td>
    <td class="row:reverse">
      Define flex
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
      Define flex direction
    </td>
  </tr>
  <tr>
    <td data-label="Properties">
      <code>flex-wrap</code><span class="color:orange">&#42;</span>
    </td>
    <td data-label="Attributes">
      <code>:nowrap</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td class="row:reverse">
      Enable/disable flex wrap
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
      Define flex order
    </td>
  </tr>
</table>
<p class="margin-top:2 font-size:tiny color:orange">
  &#42; These properties have a default values set when used without modifiers.
</p>
