+++
title = "Theming"
date = "2018-04-11T09:16:45+12:00"
family = "Getting Started"
draft = false
description = "Extend existing components or create new ones to suit your need."
+++

### Customization

ZapCSS is designed to fit naturally into any project environment. There are many ways of overriding and theming your project, the following are various ways you can extend, customize or override variables to suit your needs.

**Overriding File Structure**

One of the easiest ways to customize ZapCSS is to create your own custom `.scss` file and importing this into zap.scss as part of the build process.

```html
root
├── dist
│   ├── production.css
│   └── production.js
└── src
    ├── zap.scss
    └── your-custom-css.scss // imported into zap.scss
```
<div class="margin-bottom:u2"></div>

As your project grows it is recommended that you organize your future components based on the framework's file category structure:

```html
root/
├── dist
│   ├── production.css
│   └── production.js
└── src
    ├── core
    │   ├── base
    │   ├── layout
    │   ├── module
    │   ├── single
    │   └── utility
    │
    ├── your-project
    │   ├── base
    │   ├── layout
    │   ├── module
    │   │   ├── m-your-custom-module-1.scss // imported into zap.scss
    │   │   └── m-your-custom-module-2.scss // imported into zap.scss
    │   ├── single
    │   └── utility
    │
    └── zap.scss
```
<div class="margin-bottom:u4"></div>

**SCSS Variables & Sass Maps**

Core theme settings can be set using Sass variables and Sass maps, these are an essential part of the build process. Refer to the `default.variables` file for a full list of variables and maps. Note, these are **variable defaults** meaning, they can be overwritten. Import your custom variables before `default.variables` to take advantage of this feature.

{{% codeblock key="language" definition="scss" margin="bottom" %}}
```scss
$levels: 5 !default;
$levels: 5 !default;
$columns: 12 !default;
$max-width: 1440px !default;
$radius: 5px !default;
$background: #fbfcfd !default;
...

$font-weights: (
  light: 300,
  regular: 400,
  medium: 500,
  bold: 600,
  heavy: 700
) !default;
...
```
{{% /codeblock %}}

<div class="margin-bottom:u4"></div>

**Overriding Custom Properties**

During the build process, global and local component specific custom properties are generated. You can redeclare these root properties override its setting. Refer to the `b-root.component` for all available global custom properties.

{{% codeblock key="language" definition="css" margin="bottom" %}}
```css
:root {
	/* global custom property */
	--font-family: 'Camphor Web', sans-serif;

	/* local, component specific custom property */
	--button__padding: .9em 1em;
	--button__outline-weight: 2px;
	--button__radius: var(--radius);
	--button__font-family: var(--font-family);
	--button__font-weight: var(--regular);
	--button__transition: all 0.2s ease;
}
```
{{% /codeblock %}}

Depending on the complexity you can follow one or all of these methods to customize your project.
