+++
title = "Card"
date = "2018-04-11T09:16:45+12:00"
family = "Module"
draft = false
description = "The card component is a simple card based container that holds various types of information. You can combine various style utilities to change its appearance."
+++

### Basic Usage

The card module contains header, content and footer child elements. You can also apply `elevate` component to modify the look.

<div class="row row-gutter:2 margin-bottom:u4 margin-top:10">
  <div class="column:12 column@sm:6">
    <div class="card elevate border:none margin-bottom:6">
      <div class="card/header padding:u0">
        <img src="https://i.imgur.com/Ig4qpjc.jpg" class="media">
      </div>
      <div class="card/content border-bottom">
        <div class="flag flag-gutter:1 margin-bottom:6">
          <div class="flag/item">
            <img src="https://pbs.twimg.com/profile_images/803356024690216960/CH3i813s_400x400.jpg" class="media border-radius:round media-size:2 fill:primary">
          </div>
          <div class="flag/item">
            <div>
              <h6 class="margin:0 font-weight:bold color:black font-height:0">Jin Park</h6>
              <span class="font-size:tiny font-height:0">@zapcss</span>
            </div>
          </div>
        </div>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus nec iaculis mauris. <a href="#">@zapcss</a>. <a href="#">#css</a> <a href="#">#responsive</a>
        </p>
      </div>
      <div class="card/footer padding:u0">
        <a href="#" class="button button-size:4 button-style:flat fill:blue width:100% border-radius:sharp border-radius-bottom">
          Send Message
        </a>
      </div>
    </div>
  </div>
  <div class="column:12 column@sm:6">
    <div class="card border-style:radius margin-bottom:6">
      <div class="card/content">
        <h6 class="font font-weight:bold margin-bottom:6">Step 1 of 2</h6>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus nec iaculis mauris. <a href="#">@zapcss</a>. <a href="#">#css</a> <a href="#">#responsive</a></p>
        <a href="#" class="button button-size:3 button-grow:1 fill:blue elevate font-weight:medium">
          Get Started
        </a>
      </div>
    </div>
  </div>
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="card elevate border:none">
  <div class="card/header">
    ...
  </div>
  <div class="card/content">
    ...
  </div>
  <div class="card/footer padding:u0">
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
{{% /codeblock %}}

### Local Variables

You can override styling using the following local variables.

{{% codeblock key="language" definition="css" margin="bottom" %}}
```css
:root {
	--card-bg: var(--white);
	--card-radius: var(--radius);
	--card-header-padding: var(--u2);
	--card-content-padding: var(--u2);
	--card-footer-padding: var(--u1);
}
```
{{% /codeblock %}}
