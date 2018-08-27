+++
title = "Media"
date = "2018-04-11T09:16:45+12:00"
family = "Single"
draft = false
description = "The media component formats images provides useful preset sizes."
+++

### Basic Usage

<div class="margin-bottom:u6 max-width:14">
  <img src="http://via.placeholder.com/500x500" class="media">
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<img src="http://via.placeholder.com/500x500" class="media">
```
{{% /codeblock %}}


### Corner Shapes

Various corner styles can be applied with the `border-radius` component property.

<div class="margin-bottom:u6 max-width:10">
  <img src="http://via.placeholder.com/500x500" class="media">
</div>

<div class="margin-bottom:u6 max-width:10">
  <img src="http://via.placeholder.com/500x500" class="media border-radius">
</div>

<div class="margin-bottom:u6 max-width:10">
  <img src="http://via.placeholder.com/500x500" class="media border-radius:round">
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<img src="http://via.placeholder.com/500x500" class="media">
<img src="http://via.placeholder.com/500x500" class="media border-radius">
<img src="http://via.placeholder.com/500x500" class="media border-radius:round">
```
{{% /codeblock %}}

### Inline Images

The `image` component by default inherits the display block property however you can override this to be any type with the `display` component.

<img src="http://via.placeholder.com/1200x200" class="media width:100% margin-bottom:u6">
<img src="http://via.placeholder.com/200x200" class="media display:inline-block">
<img src="http://via.placeholder.com/200x200" class="media display:inline-block">


{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<img src="http://via.placeholder.com/1200x200" class="media width:100% margin-bottom:u6">
<img src="http://via.placeholder.com/200x200" class="media display:inline-block">
<img src="http://via.placeholder.com/200x200" class="media display:inline-block">
```
{{% /codeblock %}}

### Preset Sizes

The `image-size` property provides useful preset sizes for things like thumbnails and profile pictures.

<img src="http://via.placeholder.com/200x200" class="media media-size:xs margin-bottom:u6">
<img src="http://via.placeholder.com/200x200" class="media media-size:sm margin-bottom:u6">
<img src="http://via.placeholder.com/200x200" class="media media-size:md margin-bottom:u6">
<img src="http://via.placeholder.com/200x200" class="media media-size:lg margin-bottom:u6">
<img src="http://via.placeholder.com/200x200" class="media media-size:xl margin-bottom:u6">

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<img src="http://via.placeholder.com/200x200" class="media media-size:xs">
<img src="http://via.placeholder.com/200x200" class="media media-size:sm">
<img src="http://via.placeholder.com/200x200" class="media media-size:md">
<img src="http://via.placeholder.com/200x200" class="media media-size:lg">
<img src="http://via.placeholder.com/200x200" class="media media-size:xl">
```
{{% /codeblock %}}

### Local Variables

You can override styling using the following local variables.

{{% codeblock key="language" definition="css" margin="bottom" %}}
```css
$media-levels: 5 !default;
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
      <code>:2</code> ... <code>:10</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td class="row:reverse">
      Set image size
    </td>
  </tr>
</table>