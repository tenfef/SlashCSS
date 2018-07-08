+++
title = "Card"
date = "2018-04-11T09:16:45+12:00"
draft = false
description = "The card component is a simple card based container that holds various types of information."
+++


##### Basic Usage

The card module contains header, content and footer child elements. There are two types of card styles available, elevated (default) and flat. By default child elements has padding however, this can be removed with the `-flush` modifier.

<div class="row row-gutter:2 margin-bottom:2">
  <div class="column:6">
    <div class="card margin-bottom:2">
      <div class="card/content padding:none">
        <img src="https://i.imgur.com/Ig4qpjc.jpg" class="image">
      </div>
      <div class="card/content border-bottom">
        <div class="row:media row-gutter:1 margin-bottom:2">
          <div class="column">
            <span class="image image-shape:round image-size:2 fill:primary">
              <img src="https://pbs.twimg.com/profile_images/803356024690216960/CH3i813s_400x400.jpg">
            </span>
          </div>
          <div class="column display:flex align-item:middle">
            <div>
              <p class="font font-weight:bold color:black font-height:0">Jin Park</p>
              <span class="font-size:tiny font-height:0">@zapcss</span>
            </div>
          </div>
        </div>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus nec iaculis mauris. <a href="#">@zapcss</a>. <a href="#">#css</a> <a href="#">#responsive</a>
        </p>
      </div>
      <a href="#" class="card/content height:3 align:center fill:background">
        Get started
      </a>
    </div>
  </div>
  <div class="column:6">
    <div class="card border-style:radius margin-bottom:2">
      <div class="card/content">
        <h6 class="font font-weight:medium margin-bottom:2">Step 1 of 2</h6>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus nec iaculis mauris. <a href="#">@zapcss</a>. <a href="#">#css</a> <a href="#">#responsive</a></p>
        <div>
        <a href="#" class="button button-size:2 button-grow:1 button-style:physical font-weight:medium">
          Get Started
        </a>
        </div>
      </div>
    </div>
  </div>
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="card">
  <div class="card/header -flush">
    ...
  </div>
  <div class="card/content">
    ...
  </div>
  <div class="card/footer">
    ...
  </div>
</div>

<div class="card -flat">
  <div class="card/content">
    ...
  </div>
  <div class="card/footer">
    ...
  </div>
</div>
```
{{% /codeblock %}}
