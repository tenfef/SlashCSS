+++
title = "Elevate"
date = "2018-04-11T09:16:45+12:00"
family = "Utility"
draft = false
description = "A simple component for adding box shadow universally across any element"
+++

### Basic Usage

The `elevate` component can be applied to any type of component.

<button class="button fill:white elevate button-grow:2 border-radius:round color:grey-d1 margin-bottom:2">Button</button>

<div class="padding:4 fill:white border-radius elevate margin-bottom:9">
	<div class="row:media row-gutter:1">
		<div class="column">
			<img src="https://pbs.twimg.com/profile_images/803356024690216960/CH3i813s_400x400.jpg" class="media border-radius:round media-size:2 fill:primary elevate">
		</div>
		<div class="column display:flex align-item:middle">
			<div>
				<p class="margin:0 font-weight:medium color:black font-height:1">Jin Park</p>
				<span class="font-size:tiny font-height:0">@zapcss</span>
			</div>
		</div>
	</div>
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<button class="button fill:white elevate button-grow:5 border-radius:round color:grey-d1 margin-bottom:2">Button</button>
<button class="button fill:blue elevate button-grow:5 border-radius:round margin-bottom:2">Button</button>

<div class="padding:4 fill:white border-radius elevate margin-bottom:4">
	<div class="flag flag-gutter:1">
		<div class="flag/item">
			<img src="https://pbs.twimg.com/profile_images/803356024690216960/CH3i813s_400x400.jpg" class="media border-radius:round media-size:5 fill:primary elevate">
		</div>
		<div class="flag/item">
			<div>
				<p class="margin:0 font-weight:medium color:black font-height:0">Jin Park</p>
				<span class="font-size:tiny font-height:0">@zapcss</span>
			</div>
		</div>
	</div>
</div>
```
{{% /codeblock %}}
