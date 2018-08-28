+++
title = "Clear"
date = "2018-04-11T09:16:45+12:00"
family = "Utility"
draft = false
description = "The clear component applies basic clear properties to block elements"
+++

### Clear

Defined with `clear`. Provides a simple way of apply clear both.

<div class="float:left column:6 padding:5 fill:grey-l4 margin-bottom:u2">

</div>

<div class="clear fill:grey-l5 margin-bottom:u2">
  <div class="column:12 padding:5 fill:grey-l3">

  </div>
</div>

```html
<div class="float:left">
  Floating Element
</div>
<div class="clear">

</div>
```

### Clearfix

Defined with `clear-fix`. Provides a simple way of apply clearfixes to block elements that contain floating elements.

<div class="clear-fix fill:grey-l5 margin-bottom:u2">
  <div class="float:left column:6 padding:5 fill:grey-l3">

  </div>
</div>

```html
<div class="clear-fix">
  <div class="float:left">

  </div>
</div>
```
