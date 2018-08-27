+++
title = "Installation"
date = "2018-04-11T09:16:45+12:00"
family = "Getting Started"
draft = false
description = "Quick start guide for installing your first SlashCSS project."
+++

### The Quick Way

There are two ways you can get started. To pull in SlashCSS for quick test run the quickest way is to include the latest Slash CSS and JS files into your project. This will provide your project with all the basic component and give your stylesheet access to global and local CSS variables.

```html
<link rel="stylesheet" href="https://rawgit.com/atjinsu/SlashCSS/master/static/assets/css/main.css">
<script src="https://rawgit.com/atjinsu/SlashCSS/master/static/assets/js/main.js"></script>
```

### Recommended Way

To setup this project and take full advantage of its customization features, the recommended way is to clone the github repository and include the src build files into your project folder. **SlashCSS is built on the Sass pre-processor then converted into PostCSS using gulp** however this can be substituted for any other build tool of your choosing. Gulp is also used to further concatenate, minify and autoprefix. For more info on gulp visit the [homepage](https://gulpjs.com/).

###### Step 1. Clone Repository

Clone the SlashCSS project repository from Github and include the src directory as part of your build process.

```terminal
git clone https://github.com/atjinsu/SlashCSS.git
```

###### Step 2. Configure gulpfile.js & Process SCSS

Run the `gulp watch` command or manually process `main.scss`. The component directory and `build.variables` need to be included in the same directory as your `main.scss`.

```terminal
src/gulpfile.js
src/css/main.scss
src/js/main.js
```

###### Step 3. Link the processed CSS & JS file

```html
<link rel="stylesheet" href="/assets/css/main.css">
<script src="/assets/js/main.js"></script>
```

> The `main.scss` file is the main source file that handles including of all the components and overrides. This is where you should write your custom project css. The `build.variables` includes global sass variables and maps to help build out Slash components. During this process, some of the scss variables are converted css custom properties. SlashCSS is designed to be used with css custom properties however you can enable cssnext in the gulp process to allow for deeper browser support.

### Still Confused?

SlashCSS was designed to be useful for a wide range of developers. Although the quick way allows for quick project setup, it's potential really shines once the proper configuration requirements are met. If you're not familiar with this style of project setup or need further assistance contact me through [twitter](https://twitter.com/SlashCSS/) or email and I'd be happy to help!

<a href="mailto:made@slashcss.com" class="button button-style:outline font-size:body font-case:none color:black">
  <i class="fas fa-envelope margin-right:u2"></i>
  Get in touch
</a>
