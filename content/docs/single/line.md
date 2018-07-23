+++
title = "Line"
date = "2018-04-11T09:16:45+12:00"
draft = false
description = "The line component is similar to the hr element and is used as content dividers."
+++

### Basic Usage

The Single line `line` creates a soft horizontal rules that divide sections.

<div class="line"></div>

{{% codeblock key="language" definition="html" margin="top" %}}
```html
<div class="line"></div>
```
{{% /codeblock %}}


### Line Colors

You can change the color of the line with the `fill` component

<div class="line fill:red margin-bottom:2"></div>
<div class="line fill:pink margin-bottom:2"></div>
<div class="line fill:violet margin-bottom:2"></div>
<div class="line fill:purple margin-bottom:2"></div>
<div class="line fill:navy margin-bottom:2"></div>
<div class="line fill:blue margin-bottom:2"></div>
<div class="line fill:teal margin-bottom:2"></div>
<div class="line fill:green margin-bottom:2"></div>
<div class="line fill:lime margin-bottom:2"></div>
<div class="line fill:yellow margin-bottom:2"></div>
<div class="line fill:orange margin-bottom:2"></div>
<div class="line fill:brown margin-bottom:2"></div>
<div class="line fill:grey margin-bottom:2"></div>
<div class="line fill:white margin-bottom:2"></div>
<div class="line fill:black margin-bottom:6"></div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="line fill:red margin-bottom:2"></div>
<div class="line fill:pink margin-bottom:2"></div>
<div class="line fill:violet margin-bottom:2"></div>
<div class="line fill:purple margin-bottom:2"></div>
<div class="line fill:navy margin-bottom:2"></div>
<div class="line fill:blue margin-bottom:2"></div>
<div class="line fill:teal margin-bottom:2"></div>
<div class="line fill:green margin-bottom:2"></div>
<div class="line fill:lime margin-bottom:2"></div>
<div class="line fill:yellow margin-bottom:2"></div>
<div class="line fill:orange margin-bottom:2"></div>
<div class="line fill:brown margin-bottom:2"></div>
<div class="line fill:grey margin-bottom:2"></div>
<div class="line fill:white margin-bottom:2"></div>
<div class="line fill:black margin-bottom:2"></div>
```
{{% /codeblock %}}

### Local Variables

You can override styling using the following local variables.

{{% codeblock key="language" definition="css" margin="bottom" %}}
```css
:root {
  --line-weight: 1px;
}
```
{{% /codeblock %}}
