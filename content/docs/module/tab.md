+++
title = "Tab"
date = "2018-04-11T09:16:45+12:00"
draft = false
description = "Tab is a javascript component that allows for hiding and showing of content using tabs to navigate."
+++

### Basic Usage

Defined with class `tab` and initialied with Javascript, Tab requires the header and content items to have atleast one `is-active` state.

<div class="tab margin-bottom:7">
  <div class="tab/header">
    <a href="#panel1" class="tab/item is-active">
      Tab 1
    </a>
    <a href="#panel2" class="tab/item">
      Tab 2
    </a>
    <a href="#panel3" class="tab/item">
      Tab 3
    </a>
  </div>
  <div class="tab/content">
    <div id="panel1" class="tab/item is-active">
      <h5 class="font margin-bottom:2">Tab 1 Content</h5>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut vitae dui quis tellus tincidunt tempor sed sit amet eros. Phasellus in ipsum eu leo dignissim feugiat vitae vitae nunc. Pellentesque dignissim nibh sed arcu scelerisque dignissim eget rhoncus orci. Pellentesque finibus imperdiet mi, ac volutpat neque suscipit ac. Quisque faucibus sodales magna ac pretium. Curabitur enim felis, efficitur condimentum sagittis eget, aliquet sit amet diam. Ut sed pharetra nibh. Interdum et malesuada fames ac ante ipsum primis in faucibus. Proin diam nibh, feugiat ut elit imperdiet, porttitor euismod libero. Aliquam erat volutpat. Maecenas et mauris dignissim enim dictum tristique tristique a purus. Proin vel magna eget libero feugiat ultrices. Phasellus aliquet et nisi ac molestie. Proin congue nisl ac dolor volutpat cursus. Aenean rutrum libero eu diam tempor, id luctus urna dictum.
      </p>
    </div>
    <div id="panel2" class="tab/item">
      <h5 class="font margin-bottom:2">Tab 2 Content</h5>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut vitae dui quis tellus tincidunt tempor sed sit amet eros. Phasellus in ipsum eu leo dignissim feugiat vitae vitae nunc. Pellentesque dignissim nibh sed arcu scelerisque dignissim eget rhoncus orci. Pellentesque finibus imperdiet mi, ac volutpat neque suscipit ac.
      </p>
    </div>
    <div id="panel3" class="tab/item">
      <h5 class="font margin-bottom:2">Tab 3 Content</h5>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut vitae dui quis tellus tincidunt tempor sed sit amet eros. Phasellus in ipsum eu leo dignissim feugiat vitae vitae nunc. Pellentesque dignissim nibh sed arcu scelerisque dignissim eget rhoncus orci. Pellentesque finibus imperdiet mi, ac volutpat neque suscipit ac. Quisque faucibus sodales magna ac pretium. Curabitur enim felis, efficitur condimentum sagittis eget, aliquet sit amet diam. Ut sed pharetra nibh. Interdum et malesuada fames ac ante ipsum primis in faucibus. Proin diam nibh, feugiat ut elit imperdiet, porttitor euismod libero.
      </p>
    </div>
  </div>
</div>


{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="tab">
  <div class="tab/header">
    <a href="#panel1" class="tab/item is-active">
      Tab 1
    </a>
    <a href="#panel2" class="tab/item">
      Tab 2
    </a>
    <a href="#panel3" class="tab/item">
      Tab 3
    </a>
  </div>
  <div class="tab/content">
    <div id="panel1" class="tab/item is-active">
      ...
    </div>
    <div id="panel2" class="tab/item">
      ...
    </div>
    <div id="panel3" class="tab/item">
      ...
    </div>
  </div>
</div>
```

  {{% codeblock key="initializing" definition="javascript" margin="top" %}}
  ```javascript
  var tab = new Tab();
  ```
  {{% /codeblock %}}
{{% /codeblock %}}

### Tab Position

You can change the position of the header tabs with the `tab-position` property.

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="tab tab-position:left">
  ...
</div>

<div class="tab tab-position:right">
  ...
</div>

<div class="tab tab-position:bottom">
  ...
</div>
```
{{% /codeblock %}}

### Tab Reset

If you need to remove default styling and require the tab for its functional aspect only, apply the `:reset` modifier.

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="tab tab:reset">
  ...
</div>
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
      <code>tab</code>
    </td>
    <td data-label="Attributes">
      <code>:reset</code>
    </td>
    <td data-label="Responsive">
      No
    </td>
    <td class="row:reverse">
      Reset the default tab styling
    </td>
  </tr>
  <tr>
    <td data-label="Properties">
      <code>tab-position</code>
    </td>
    <td data-label="Attributes">
      <code>:left/code> <code>:right</code> <code>:bottom</code>
    </td>
    <td data-label="Responsive">
      No
    </td>
    <td class="row:reverse">
      Set the position of tab header items
    </td>
  </tr>
</table>


### JS Settings

<table class="table width:100% table:pile table@sm:unpile">
  <thead>
    <tr>
      <th>
        <strong>Setting</strong>
      </th>
      <th>
        <strong>Default</strong>
      </th>
      <th>
        <strong>Description</strong>
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td data-label="Setting">
        <code>element</code>
      </td>
      <td data-label="Default">
        <code>.tab</code>
      </td>
      <td data-label="Description">
        Define the element class name to initialize.
      </td>
    </tr>
  </tbody>
</table>
