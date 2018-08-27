+++
title = "Fundamentals"
date = "2018-04-11T09:16:45+12:00"
family = "Getting Started"
draft = false
description = "The fundamental conventions and rules of SlashCSS."
+++

### Structure & Organization

At its core, SlashCSS organizes its components into 5 different categories laid out in order of specificity: **Base**, **Layout**, **Module**, **Single** and **Utility**. This structure is an simplified adaptation of Jonathan Snook's SMACSS and the Inverted Triangle methodology.

```html
/base
/layout
/module
/single
/utility
```

###### Base

The **Base folder** is the foundation of your project and contains CSS Normalize/Resets, HTML/body and element declarations, global css variables etc. Similar to a construction site, this is something we set once and expect to be stable. Treat this folder as the floor plan we build our project on.

###### Layout

The **Layout folder** contains position related components that only manipulate the positioning of content such as grids, flag object and wrappers. These components structure the layout and orientation of your page and or components.

###### Module

The **Module folder** contains re-usable components that house smaller child elements but are treated as one single entity. These include tables, cards, lists, forms and etc.

###### Single

The **Single folder** contains small and or interactive components that are styled independent of its parent container such as buttons and labels. These are the smallest unit of visual components.

###### Utility

The **Utility folder** contains useful single purpose components such as hiddens, floats and aligns etc. The purpose of utility classes is to apply immutable behavioral changes.

### Naming Rules

SlashCSS takes pride in its naming convention, so much infact that the name of the framework was based on its unique slash based BEM system. Unlike the traditional BEM method of using double underscores and hyphens to define child elements and modifiers, SlashCSS uses 3 types of single character notations to apply meaning to each class. All child elements are defined with `/`, responsiveness with `@` and modifiers with `:`.

```html
<ul class="list">
  <li class="list/item fill@lg:red">
    <!-- this list item becomes red at large screen -->
  </li>
  <li class="list/item">
    ...
  </li>
  <li class="list/item">
    ...
  </li>
</ul>
```

### Responsive Rules

SlashCSS uses a mobile-first approach to styling this means that styles are applied first to mobile devices. Complex styles and other overrides for larger screens are then applied via media queries. There are three media query sizes available: `sm`, `md`, `lg`.

```html
<div class="column:12 column@sm:10 column@md:6">
  <!-- 12 column on mobile, 10 on tablet and 6 on laptop or larger -->
</div>
```

### Sizing Rules

SlashCSS utilises 2 types of sizing modifier notations. `xs`,`sm`, `md`, `lg`, `xl` are general purpose size variants for components such as buttons and media sizes, these units generally modifer the size of a component in both horizontal and vertical direction. For specific rem based units for things such as heights and margins, SlashCSS provides a range of unit scales, view the unit chart to see visual representation of this scale.

```html
<button class="button button-size:xs">Button</button>
<button class="button button-size:sm">Button</button>
<button class="button button-size:md">Button</button>
<button class="button button-size:lg">Button</button>
<button class="button button-size:xl">Button</button>

<div class="margin-bottom:u2"></div>
<div class="margin-bottom:u4"></div>
<div class="margin-bottom:u6"></div>
...
```

### Common Taxonomies

To ensure naming simplicity and consistency many components share the same child element names. Child containers are defined with `block/content` and repeating elements are defined with `block/item`.

```html
<ul class="list">
  <li class="list/item">
    ...
  </li>
  <li class="list/item">
    ...
  </li>
</ul>

<div class="card">
  <div class="card/content">
    ...
  </div>
</div>

<div class="menu">
  <div class="menu/content">
    <div class="menu/item">
      ...
    </div>
    <div class="menu/item">
      ...
    </div>
  </div>
</div>
```

### Further Concepts

When building sites with SlashCSS you build the structure first, populate this with elements then refine its behavior with utility classes. Many of the common utility based classes are extracted out to help you avoid excessive css bloat and maintain a healthy object-oriented codebase.

> SlashCSS is a hybrid utility based framework and distinguishes components into three conceptual types, **landscapes**, **objects** and **behaviors**. Landscape based components (layouts) their sole role is to move or create boundary. Object based components (modules and singles) populate the landscape and their sole role is to exist and interact. Behaviors (utilities) influence the behavior of all things. By distinguishing the components into these three categories helps us to build a mental model in our minds when thinking about site design.
