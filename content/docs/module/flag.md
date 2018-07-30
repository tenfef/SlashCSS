+++
title = "Flag"
date = "2018-04-11T09:16:45+12:00"
family = "Module"
draft = false
description = "The markup component formats general paragraph and heading elements for readability."
+++

### Flag Object

The flag object is similar to Nicole Sullivan's media object, however is not limited to just image and body. You can include as many child items as you like.

<div class="flag flag-gutter:1">
  <div class="flag/item">
    <img src="https://pbs.twimg.com/profile_images/803356024690216960/CH3i813s_400x400.jpg" class="media border-radius:round media-size:5 fill:primary">
  </div>
  <div class="flag/item">
    <div>
      <h6 class="font-weight:medium color:black font-height:0 margin-bottom:none">Jin Park</h6>
      <span class="font-size:tiny font-height:0">@zapcss</span>
    </div>
  </div>
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="flag">
  <div class="flag/item">
    Image Left
  </div>
  <div class="flag/item">
    Text Right
  </div>
</div>
```
{{% /codeblock %}}

### Local Variables

You can override styling using the following local variables.

{{% codeblock key="language" definition="css" margin="bottom" %}}
```css
$flag-gutters: 4 !default;
```
{{% /codeblock %}}
