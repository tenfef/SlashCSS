+++
title = "Line"
date = "2018-04-11T09:16:45+12:00"
family = "Single"
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

<div class="line fill:red margin-bottom:u4"></div>
<div class="line fill:pink margin-bottom:u4"></div>
<div class="line fill:violet margin-bottom:u4"></div>
<div class="line fill:purple margin-bottom:u4"></div>
<div class="line fill:navy margin-bottom:u4"></div>
<div class="line fill:blue margin-bottom:u4"></div>
<div class="line fill:teal margin-bottom:u4"></div>
<div class="line fill:green margin-bottom:u4"></div>
<div class="line fill:lime margin-bottom:u4"></div>
<div class="line fill:yellow margin-bottom:u4"></div>
<div class="line fill:orange margin-bottom:u4"></div>
<div class="line fill:brown margin-bottom:u4"></div>
<div class="line fill:grey margin-bottom:u4"></div>
<div class="line fill:white margin-bottom:u4"></div>
<div class="line fill:black margin-bottom:u6"></div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="line fill:red"></div>
<div class="line fill:pink"></div>
<div class="line fill:violet"></div>
<div class="line fill:purple"></div>
<div class="line fill:navy"></div>
<div class="line fill:blue"></div>
<div class="line fill:teal"></div>
<div class="line fill:green"></div>
<div class="line fill:lime"></div>
<div class="line fill:yellow"></div>
<div class="line fill:orange"></div>
<div class="line fill:brown"></div>
<div class="line fill:grey"></div>
<div class="line fill:white"></div>
<div class="line fill:black"></div>
```
{{% /codeblock %}}

### Local Variables

You can override this component using the following local variables.

{{% codeblock key="language" definition="css" margin="bottom" %}}
```css
:root {
  --line-weight: 1px;
}
```
{{% /codeblock %}}
