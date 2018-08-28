+++
title = "Media"
date = "2018-04-11T09:16:45+12:00"
family = "Single"
draft = false
description = "The media component formats images provides useful preset sizes."
+++

### Basic Usage

<div class="margin-bottom:u6 max-width:14">
  <img src="https://placeimg.com/800/500/nature" class="media max-width:300px">
</div>

```html
<img src="https://placeimg.com/800/500/nature" class="media">
```


### Corner Shapes

Various corner styles can be applied with the `border` component.

<div class="margin-bottom:u6 max-width:10">
  <img src="https://placeimg.com/500/500/nature" class="media media-size:xl">
</div>

<div class="margin-bottom:u6 max-width:10">
  <img src="https://placeimg.com/500/500/nature" class="media media-size:xl border-radius">
</div>

<div class="margin-bottom:u6 max-width:10">
  <img src="https://placeimg.com/500/500/nature" class="media media-size:xl border-radius:round">
</div>

```html
<img src="https://placeimg.com/500/500/nature" class="media">
<img src="https://placeimg.com/500/500/nature" class="media border-radius">
<img src="https://placeimg.com/500/500/nature" class="media border-radius:round">
```

### Inline Images

The `image` component by default inherits the display block property however you can override this to be any type with the `display` component.

<img src="https://placeimg.com/400/400/nature" class="media media-size:xl display:inline-block">
<img src="https://placeimg.com/400/400/people" class="media media-size:xl display:inline-block">


```html
<img src="https://placeimg.com/400/400/nature" class="media display:inline-block">
<img src="https://placeimg.com/400/400/people" class="media display:inline-block">
```

### Preset Sizes

The `image-size` property provides useful preset sizes for things like thumbnails and profile pictures.

<img src="https://placeimg.com/400/400/nature" class="media media-size:xs margin-bottom:u6">
<img src="https://placeimg.com/400/400/nature" class="media media-size:sm margin-bottom:u6">
<img src="https://placeimg.com/400/400/nature" class="media media-size:md margin-bottom:u6">
<img src="https://placeimg.com/400/400/nature" class="media media-size:lg margin-bottom:u6">
<img src="https://placeimg.com/400/400/nature" class="media media-size:xl margin-bottom:u6">

```html
<img src="https://placeimg.com/400/400/nature" class="media media-size:xs">
<img src="https://placeimg.com/400/400/nature" class="media media-size:sm">
<img src="https://placeimg.com/400/400/nature" class="media media-size:md">
<img src="https://placeimg.com/400/400/nature" class="media media-size:lg">
<img src="https://placeimg.com/400/400/nature" class="media media-size:xl">
```

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
      <code>media</code>
    </td>
    <td data-label="Attributes">

    </td>
    <td data-label="Responsive">
      No
    </td>
    <td class="row:reverse">
      Set default media properties
    </td>
  </tr>
  <tr>
    <td data-label="Properties">
      <code>media-size</code>
    </td>
    <td data-label="Attributes">
      <code>:xs</code> <code>:sm</code> <code>:md</code> <code>:lg</code> <code>:xl</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td class="row:reverse">
      Set image size
    </td>
  </tr>
</table>
