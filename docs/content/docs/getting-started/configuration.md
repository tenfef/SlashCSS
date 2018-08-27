+++
title = "Configuration"
date = "2018-04-11T09:16:45+12:00"
family = "Getting Started"
draft = false
description = "A guide to configuring and customizing your SlashCSS project."
+++


### Setup your Project

The `build.variables` file contains all the base setting variables that is used to compile and generate the component properties.

```scss
$prefix: "" !default;
$radius: 8px !default;
$border: 1px solid var(--border-color) !default;
$transition: all .2s !default;
$shadow: 0 3px 6px 2px rgba(0,60,200,0.10);
$unit: 0.25rem !default;

...
```

Scss maps global and are used to generate each of the components.

```scss
$colors: (
  red: #FF2727,
  pink: #FF276C,
  violet: #D727FF,
  purple: #8D27FF,
  navy: #4A27FF,
  blue: #278AFF,
  teal: #00DEB1,
  green: #00B26B,
  lime: #6EDF00,
  yellow: #FFCE00,
  orange: #ff8a00,
  brown: #A83C00,
  grey: #5c789c
) !default;
```

### Global Custom Properties

Common global variables are converted to CSS custom properties and are accessible in post processed state. To view all global custom properties that are available refer to `root.base`.

```scss
:root {

  --radius: #{$radius};
  --border: #{$border};
  --transition: #{$transition};
  --shadow: #{$shadow};

  ...
}
```

### Local Custom Properties

In addition to global custom properties, components feature local custom properties and scss build variables.

```scss
/************************************************************
BUTTON
************************************************************/

$button-sizes: 5 !default;

:root {
  --button-outline-weight: 1px;
  --button-radius: 5px;
  --button-font-family: var(--font-family);
  --button-font-size: var(--micro);
  --button-font-weight: var(--medium);
}

```

### Graceful Implementation

Rather than starting a new Slash project, you may need to implement this library into your existing project. To avoid conflicts you can assign a namespace during your build process.

```scss
$prefix: "nameSpace" !default;
// would generate namespaced components .nameSpace-button .nameSpace-row etc
```

### Library Filesize

The default SlashCSS library is approx 204kb and 26kb gzipped. If you require a smaller file size you can simplify your components by reducing the local size variants within each component or reducing the number of options in the maps during your build process. Doing this will reduce the overall size quite significantly.
