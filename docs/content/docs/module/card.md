+++
title = "Card"
date = "2018-04-11T09:16:45+12:00"
family = "Module"
draft = false
description = "The card component is a simple self container container."
+++

### Basic Usage

The card module contains header, content and footer child elements. You can also apply `elevate` component to modify the look.

<div class="row row-gutter:u6 margin-bottom:u4 margin-top:10">
  <div class="column:12 column@sm:6">
    <div class="card elevate margin-bottom:u6">
      <div class="card/header padding:u0">
        <img src="https://i.imgur.com/Ig4qpjc.jpg" class="media">
      </div>
      <div class="card/content border-bottom">
        <div class="flag flag-gutter:u4 margin-bottom:u4">
          <div class="flag/item">
            <img src="/assets/images/jin.jpg" class="media elevate border border-width:3px border-color:white media-size:md border-radius:round" alt="Jin Su Park">
          </div>
          <div class="flag/item font-height:1">
            <h6 class="margin:u0">Jin Su Park</h6>
            <p>@slashcss</p>
          </div>
        </div>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus nec iaculis mauris. <a href="#">@zapcss</a>. <a href="#">#css</a> <a href="#">#responsive</a>
        </p>
      </div>
      <div class="card/footer padding:u0">
        <a href="#" class="flex button button-style:flat fill:blue width:100% border-radius:sharp border-radius-bottom">
          Send Message
        </a>
      </div>
    </div>
  </div>
  <div class="column:12 column@sm:6">
    <div class="card border-style:radius margin-bottom:u6">
      <div class="card/content">
        <h6 class="font font-weight:bold margin-bottom:u6">Step 1 of 2</h6>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus nec iaculis mauris. <a href="#">@zapcss</a>. <a href="#">#css</a> <a href="#">#responsive</a></p>
        <a href="#" class="button button-grow:1 fill:blue elevate font-weight:medium">
          Get Started
        </a>
      </div>
    </div>
  </div>
</div>

```html
<div class="card elevate">
  <div class="card/content">
    ...
  </div>
  <div class="card/content">
    ...
  </div>
  <div class="card/content padding:u0">
    <a href="#" class="button button-style:flat fill:blue width:100% border-radius:sharp border-radius-bottom">
      Send Message
    </a>
  </div>
</div>

<div class="card">
  <div class="card/content">
    ...
  </div>
</div>
```

### Local Variables

You can override this component using the following local variables.

```scss
:root {
	--card-bg: var(--white);
	--card-radius: var(--radius);
	--card-content-padding: var(--u6);
}
```
