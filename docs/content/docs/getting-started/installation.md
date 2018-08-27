+++
title = "Installation"
date = "2018-04-11T09:16:45+12:00"
family = "Installation"
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

To setup this project and take full advantage of its customization features, the recommended way is to clone the github repository and include the src build files into your project folder. **SlashCSS is built on the Sass pre-processor then converted into PostCSS using gulp** however this can be substituted for any other build tool of your choosing. Gulp is also used to further concatenate, minify and autoprefix.

###### Step 1. Clone Repository

Clone the SlashCSS project repository from Github.

```terminal
git clone https://github.com/atjinsu/SlashCSS.git
```

###### Step 2. Clone Repository
```terminal
git clone https://github.com/atjinsu/SlashCSS.git
```

###### Step 2. Clone Repository
```terminal
git clone https://github.com/atjinsu/SlashCSS.git
```

###### Step 2. Clone Repository
```terminal
git clone https://github.com/atjinsu/SlashCSS.git
```

###### Step 2. Clone Repository
```terminal
git clone https://github.com/atjinsu/SlashCSS.git
```




1. Download or clone **<a href="https://github.com/zapFramework/zapCSS">repository</a>**.
2. Include the CSS and JS files found in the dist folder.

**Build Process**

ZapCSS utilizes a combination of Gulp, SCSS and PostCSS to build the project. At its core, Gulp runs three tasks `zap-css`, `zap-js` and `zap-media` to process and compile each of the asset groups. The following is a breakdown of the build process in more detail.

1. SCSS variables are preprocssed to build out the various component library
2. This is then parsed through PostCSS for autoprefixing, media query grouping, and minification
3. Core javascript files are concatenated and minified
4. Image files are compressed

Refer to `gulpfile.js` for a detailed view of how each of these assets are processed. Feel free to customise the gulpfile to suit your project.

### Browser Support

**ZapCSS supports the latest, stable releases of all major browsers and platforms**. On Windows, we support Internet Explorer 11 / Microsoft Edge. By default PostCSS's cssnext plugin converts your CSS custom properties to support IE11, however you can disable cssnext to retain native css variables.

### Importance of Green CSS

The life of any project lives on after its inception. Like most things, your project will eventually need to evolve and grow. In order to perform maintanence and style updates without incurring unnecessary debt your CSS should be kept well organized, modular and minimal.

Badly maintained CSS can be frustrating to work as you spend more time fighting against your stylesheet as oppose to working with it. This will eventually reduce your efficiency and slow down development.

So how do you organize your css to be simple and manageable? How do you deal with overrides and CSS specificity? How do you reduce bloat, increasing re-usability and performance? Let's begin our journey with a simple but crucial concept, file organization.
