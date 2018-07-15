+++
title = "Image"
date = "2018-04-11T09:16:45+12:00"
draft = false
description = "The image component formats images provides useful preset sizes."
+++

##### Basic Usage

<div class="margin-bottom:2 max-width:20">
  <img src="http://via.placeholder.com/500x500" class="image">
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<img src="http://via.placeholder.com/500x500" class="image">
```
{{% /codeblock %}}


##### Corner Shapes

Various corner styles can be applied with the `border-radius` component property.

<div class="margin-bottom:2 max-width:10">
  <img src="http://via.placeholder.com/500x500" class="image">
</div>

<div class="margin-bottom:2 max-width:10">
  <img src="http://via.placeholder.com/500x500" class="image border-radius">
</div>

<div class="margin-bottom:2 max-width:10">
  <img src="http://via.placeholder.com/500x500" class="image border-radius:round">
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<img src="http://via.placeholder.com/500x500" class="image">
<img src="http://via.placeholder.com/500x500" class="image border-radius">
<img src="http://via.placeholder.com/500x500" class="image border-radius:round">
```
{{% /codeblock %}}

##### Inline Images

The `image` component by default inherits the display block property however you can override this to be any type with the `display` component.

<img src="http://via.placeholder.com/1200x200" class="image width:100% margin-bottom:2">
<img src="http://via.placeholder.com/200x200" class="image display:inline-block">
<img src="http://via.placeholder.com/200x200" class="image display:inline-block">


{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<img src="http://via.placeholder.com/1200x200" class="image width:100% margin-bottom:2">
<img src="http://via.placeholder.com/200x200" class="image display:inline-block">
<img src="http://via.placeholder.com/200x200" class="image display:inline-block">
```
{{% /codeblock %}}

##### Preset Sizes

The `image-size` property provides useful preset sizes for things like thumbnails and profile pictures.

<img src="http://via.placeholder.com/200x200" class="image image-size:2 margin-bottom:1">
<img src="http://via.placeholder.com/200x200" class="image image-size:3 margin-bottom:1">
<img src="http://via.placeholder.com/200x200" class="image image-size:4 margin-bottom:1">
<img src="http://via.placeholder.com/200x200" class="image image-size:5 margin-bottom:1">
<img src="http://via.placeholder.com/200x200" class="image image-size:6 margin-bottom:1">
<img src="http://via.placeholder.com/200x200" class="image image-size:7 margin-bottom:1">
<img src="http://via.placeholder.com/200x200" class="image image-size:8 margin-bottom:1">
<img src="http://via.placeholder.com/200x200" class="image image-size:9 margin-bottom:1">
<img src="http://via.placeholder.com/200x200" class="image image-size:10 margin-bottom:1">

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<img src="http://via.placeholder.com/200x200" class="image image-size:2">
<img src="http://via.placeholder.com/200x200" class="image image-size:3">
<img src="http://via.placeholder.com/200x200" class="image image-size:4">
<img src="http://via.placeholder.com/200x200" class="image image-size:5">
<img src="http://via.placeholder.com/200x200" class="image image-size:6">
<img src="http://via.placeholder.com/200x200" class="image image-size:7">
<img src="http://via.placeholder.com/200x200" class="image image-size:8">
<img src="http://via.placeholder.com/200x200" class="image image-size:9">
<img src="http://via.placeholder.com/200x200" class="image image-size:10">
```
{{% /codeblock %}}

##### Local Variables

You can override styling using the following local variables.

{{% codeblock key="language" definition="css" margin="bottom" %}}
```css
$image-levels: 11 !default;
```
{{% /codeblock %}}

##### Options

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
      <code>image-size</code>
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
