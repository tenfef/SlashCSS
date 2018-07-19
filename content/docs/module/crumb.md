+++
title = "Crumb"
date = "2018-04-11T09:16:45+12:00"
draft = false
description = "The crumb component provides visual information of the current page location in context to the overall parent hierarchy."
+++

##### Basic Usage

<div class="crumb margin-bottom:2">
  <a href="#" class="crumb/item">Breadcrumb</a>
  <span class="crumb/trail">/</span>
  <a href="#" class="crumb/item">Breadcrumb</a>
  <span class="crumb/trail">/</span>
  <span class="crumb/item is-active">Current Page</span>
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<div class="crumb">
  <a href="#" class="crumb/item">Breadcrumb</a>
  <span class="crumb/trail">/</span>
  <a href="#" class="crumb/item">Breadcrumb</a>
  <span class="crumb/trail">/</span>
  <span class="crumb/item is-active">Current Page</span>
</div>
```
{{% /codeblock %}}

##### Local Root Variables

You can override styling using the following local root variables.

{{% codeblock key="language" definition="css" margin="bottom" %}}
```css
:root {
  --crumb-link-color: var(--primary-color);
  --crumb-active-color: var(--default-color);
  --crumb-trail-color: var(--grey);
  --crumb-trail-gap: 1rem;
}
```
{{% /codeblock %}}
