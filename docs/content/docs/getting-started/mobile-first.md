+++
title = "Mobile First"
date = "2018-04-11T09:16:45+12:00"
family = "Getting Started"
draft = false
description = "An indepth guide how component responsiveness are handled."
+++

### Mobile First Design

All components are designed with a mobile-first CSS approach. For larger screens there are 4 responsive breakpoints extensions that can be accessed, `sm` `md` `lg` `xl`.

You can access the responsive variables via the following:

{{% codeblock key="language" definition="scss" margin="bottom" %}}
```scss
$sm: 960px !default;
$md: 1024px !default;
$lg: 1280px !default;
$xl: 1600px !default;
```
{{% /codeblock %}}

### Responsive Modifiers

Device specific modifiers for components that support responsiveness can be applied by adding device extensions to the modifiers.

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="row">
  <div class="item -span-12 -span-md-6 -span-lg-4">
    ...
  </div>
</div>
```
{{% /codeblock %}}
