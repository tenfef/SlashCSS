+++
title = "Accordion DONE"
date = "2018-04-11T09:16:45+12:00"
draft = false
description = "Accordions are useful when you want to hide and show large content."
+++

##### Basic Usage

Basic accordion markup. To disable rotating arrows, remove the `accordion/arrow` child element. Styling is minimum to allow for easier style overrides.

<div class="accordion margin-bottom:2">
  <div class="accordion/item">
    <a class="accordion/header">
      Panel 1
      <span class="accordion/arrow"></span>
    </a>
    <div class="accordion/content">
      <div class="accordion/body">
        Pellentesque fermentum dolor. Aliquam quam lectus, facilisis auctor, ultrices ut, elementum vulputate, nunc.
      </div>
    </div>
  </div>
  <div class="accordion/item">
    <a class="accordion/header">
      Panel 2
      <span class="accordion/arrow"></span>
    </a>
    <div class="accordion/content">
      <div class="accordion/body">
        Donec nec justo eget felis facilisis fermentum. Aliquam porttitor mauris sit amet orci. Aenean dignissim pellentesque felis.
      </div>
    </div>
  </div>
  <div class="accordion/item">
    <a class="accordion/header">
      Panel 3
      <span class="accordion/arrow"></span>
    </a>
    <div class="accordion/content">
      <div class="accordion/body">
        Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Phasellus hendrerit. Pellentesque aliquet nibh nec urna. In nisi neque, aliquet vel, dapibus id, mattis vel, nisi. Sed pretium, ligula sollicitudin laoreet viverra, tortor libero sodales leo, eget blandit nunc tortor eu nibh. Nullam mollis. Ut justo. Suspendisse potenti.
      </div>
    </div>
  </div>
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="accordion js-accordion">
  <div class="accordion/item">
    <a class="accordion/header">
      Panel 1
      <span class="accordion/arrow"></span>
    </a>
    <div class="accordion/content">
      ...
    </div>
  </div>
  <div class="accordion/item">
    <a class="accordion/header">
      Panel 2
      <span class="accordion/arrow"></span>
    </a>
    <div class="accordion/content">
      ...
    </div>
  </div>
  <div class="accordion/item">
    <a class="accordion/header">
      Panel 3
      <span class="accordion/arrow"></span>
    </a>
    <div class="accordion/content">
      ...
    </div>
  </div>
</div>
```
{{% /codeblock %}}
{{% codeblock key="initializing" definition="javascript" margin="top-tight" %}}
```javascript
var zapAccordion = new ZapAccordion();
```
{{% /codeblock %}}

##### Local Variables

You can override styling using the following local variables.

{{% codeblock key="language" definition="css" margin="bottom" %}}
```css
:root {
  --accordion-fill: var(--white);
  --accordion-header-padding: var(--u1) var(--u2);
  --accordion-body-padding: var(--u2);
  --accordion-transition: var(--transition);
  --accordion-arrow-fill: var(--black);
}
```
{{% /codeblock %}}
