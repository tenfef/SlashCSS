+++
title = "Opacity"
date = "2018-04-11T09:16:45+12:00"
draft = false
description = "The opacity component manipulates the opacity property of a given element."
+++

##### Basic Usage

Defined with `u-fade`, there are 9 fade options available.

<h3 class="font u-fade-1">Fade 1</h3>
<h3 class="font u-fade-2">Fade 2</h3>
<h3 class="font u-fade-3">Fade 3</h3>
<h3 class="font u-fade-4">Fade 4</h3>
<h3 class="font u-fade-5">Fade 5</h3>
<h3 class="font u-fade-6">Fade 6</h3>
<h3 class="font u-fade-7">Fade 7</h3>
<h3 class="font u-fade-8">Fade 8</h3>
<h3 class="font -gap-2 u-fade-9">Fade 9</h3>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<h3 class="u-fade-1">Fade 1</h3>
<h3 class="u-fade-2">Fade 2</h3>
<h3 class="u-fade-3">Fade 3</h3>
<h3 class="u-fade-4">Fade 4</h3>
<h3 class="u-fade-5">Fade 5</h3>
<h3 class="u-fade-6">Fade 6</h3>
<h3 class="u-fade-7">Fade 7</h3>
<h3 class="u-fade-8">Fade 8</h3>
<h3 class="u-fade-9">Fade 9</h3>
```
{{% /codeblock %}}

##### Opacity Value Chart

{{% codeblock key="language" definition="scss" margin="bottom" %}}
```css
.u-fade {
	&-1 {
		opacity: .1;
	}
	&-2 {
		opacity: .2;
	}
	&-3 {
		opacity: .3;
	}
	&-4 {
		opacity: .4;
	}
	&-5 {
		opacity: .5;
	}
	&-6 {
		opacity: .6;
	}
	&-7 {
		opacity: .7;
	}
	&-8 {
		opacity: .8;
	}
	&-9 {
		opacity: .9;
	}
}

```
{{% /codeblock %}}
