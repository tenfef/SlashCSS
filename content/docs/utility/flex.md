+++
title = "Flex"
date = "2018-04-11T09:16:45+12:00"
draft = false
description = "The flex component takes advantage of flexbox properties providing you content alignment across the horizontal or vertical axis. The flex definition replaces the old flag module which is now deprecated."
+++

##### Basic Usage

You can initialize your flex component with `l-flex` flex requires child items and by default vertically center aligned. By default flex container will span the full width however you can turn this inline with the `-inline` modifier.

<div class="u-fill-shade-light u-pad-tight margin-bottom:2">
  <div class="l-flex -gap-2 -inline">
    <div class="l-flex__item">
      <span class="s-thumb -round u-fill-brand"></span>
    </div>
    <div class="l-flex__item">
      <h5 class="font -medium">Text Content</h5>
    </div>
  </div>
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="l-flex -fluid">
  <div class="l-flex__item">
    ...
  </div>
  <div class="l-flex__item">
    ...
  </div>
</div>
```
{{% /codeblock %}}

##### Row Direction

The `row-direction` property can be applied to control the direction of your columns. Standard media query suffixes can be applied.

<div class="row row-direction:down row-gutter:1 margin-bottom:2 align:center color:white">
  <div class="column">
    <div class="padding:1 fill:blue-light-2">
      1
    </div>
  </div>
  <div class="column">
    <div class="padding:1 fill:blue">
      2
    </div>
  </div>
</div>

<div class="row row-direction:down row-direction@sm:right row-gutter:2 margin-bottom:2 align:center color:white">
  <div class="column">
    <div class="padding:1 fill:blue-light-2">
      1
    </div>
  </div>
  <div class="column">
    <div class="padding:1 fill:blue">
      2
    </div>
  </div>
  <div class="column">
    <div class="padding:1 fill:blue">
      3
    </div>
  </div>
</div>

<div class="row row-direction:down row-direction@sm:reverse row-gutter:2 margin-bottom:2 align:center color:white">
  <div class="column">
    <div class="padding:1 fill:blue-light-2">
      1
    </div>
  </div>
  <div class="column">
    <div class="padding:1 fill:blue">
      2
    </div>
  </div>
  <div class="column">
    <div class="padding:1 fill:blue">
      3
    </div>
  </div>
</div>


{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="row row-direction:down">
  <div class="column">
    ...
  </div>
  <div class="column">
    ...
  </div>
</div>

<div class="row row-direction:down row-direction@sm:right">
  <div class="column">
    ...
  </div>
  <div class="column">
    ...
  </div>
  <div class="column">
    ...
  </div>
</div>

<div class="row row-direction:down row-direction@sm:reverse">
  <div class="column">
    ...
  </div>
  <div class="column">
    ...
  </div>
  <div class="column">
    ...
  </div>
</div>

```

##### Spacing

You can assign gutters using standard spacing modifiers, these can also be paired with device modifiers for device specificity.

<div class="l-flex -gap-1 margin-bottom:2">
  <div class="l-flex__item">
    <span class="s-thumb -round u-fill-brand"></span>
  </div>
  <div class="l-flex__item">
    <span class="s-thumb -size-2 -sharp u-fill-accent"></span>
  </div>
</div>

<div class="l-flex -gap-2 margin-bottom:2">
  <div class="l-flex__item">
    <span class="s-thumb -round u-fill-brand"></span>
  </div>
  <div class="l-flex__item">
    <span class="s-thumb -size-2 -sharp u-fill-accent"></span>
  </div>
</div>

<div class="l-flex -gap-3 margin-bottom:2">
  <div class="l-flex__item">
    <span class="s-thumb -round u-fill-brand"></span>
  </div>
  <div class="l-flex__item">
    <span class="s-thumb -size-2 -sharp u-fill-accent"></span>
  </div>
</div>

<div class="l-flex -gap-4 margin-bottom:2">
  <div class="l-flex__item">
    <span class="s-thumb -round u-fill-brand"></span>
  </div>
  <div class="l-flex__item">
    <span class="s-thumb -size-2 -sharp u-fill-accent"></span>
  </div>
</div>

<div class="l-flex -gap-5 margin-bottom:2">
  <div class="l-flex__item">
    <span class="s-thumb -round u-fill-brand"></span>
  </div>
  <div class="l-flex__item">
    <span class="s-thumb -size-2 -sharp u-fill-accent"></span>
  </div>
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="l-flex -gap-1">
  ...
</div>
<div class="l-flex -gap-2">
  ...
</div>
<div class="l-flex -gap-3">
  ...
</div>
<div class="l-flex -gap-4">
  ...
</div>
<div class="l-flex -gap-5 -gap-sm-2 -gap-lg-4">
  ...
</div>
```
{{% /codeblock %}}


##### Vertical Alignment

By default the flex component vertically aligns your child items to the center however this can be overwritten with the `-top` and `-bottom` modifiers.

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="l-flex -top">
  ...
</div>
<div class="l-flex -bottom">
  ...
</div>
```
{{% /codeblock %}}
