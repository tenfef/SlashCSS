+++
title = "Wrap DONE"
date = "2018-04-11T09:16:45+12:00"
draft = false
description = "The wrap component is a standard center aligning content container with a set maximum width."
+++

##### Basic Usage

The wrap layout definitions has float clearing properties built in.

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="wrap">
  ...
</div>
```
{{% /codeblock %}}

##### Local Variables

You can override styling using the following local variables.

{{% codeblock key="language" definition="css" margin="bottom" %}}
```css
$max-width: 1600px !default;

:root {
  --max-width: #{$max-width};
}
```
{{% /codeblock %}}

##### Options

The following modifiers are available.

<table class="table width:100% table:pile">
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
      <code>wrap</code>
    </td>
    <td data-label="Attributes">
      <code>:flush</code> <code>:unflush</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td class="row:reverse">
      Apply or remove default padding
    </td>
  </tr>
</table>
