+++
title = "Wrap"
date = "2018-04-11T09:16:45+12:00"
family = "Layout"
draft = false
description = "The wrap component is a standard center aligning content container with a set maximum width."
+++

### Basic Usage

The wrap component has float clearing properties built in.

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="wrap">
  ...
</div>
```
{{% /codeblock %}}

### Local Variables

You can override this component using the following local variables.

{{% codeblock key="language" definition="css" margin="bottom" %}}
```css
:root {
  --wrap-width: 1600px;
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
      <code>wrap</code>
    </td>
    <td data-label="Attributes">
      <code>:flush</code> <code>:unflush</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td>
      Apply or remove default padding
    </td>
  </tr>
</table>
