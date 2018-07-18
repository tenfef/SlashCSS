+++
title = "Elevate"
date = "2018-04-11T09:16:45+12:00"
draft = false
description = "A simple component for adding box shadow universally across any element"
+++

##### Basic Usage

The `elevate` component can be applied to any type of component.

<button class="button fill:white elevate button-grow:5 border-radius:round color:grey-d1 margin-bottom:2">Button</button>
<button class="button fill:blue elevate button-grow:5 border-radius:round margin-bottom:2">Button</button>

<div class="padding:2 fill:white border-radius elevate margin-bottom:4">
	<div class="row:media row-gutter:1">
		<div class="column">
			<img src="https://pbs.twimg.com/profile_images/803356024690216960/CH3i813s_400x400.jpg" class="media border-radius:round media-size:5 fill:primary elevate">
		</div>
		<div class="column display:flex align-item:middle">
			<div>
				<p class="margin:none font-weight:medium color:black font-height:0">Jin Park</p>
				<span class="font-size:tiny font-height:0">@zapcss</span>
			</div>
		</div>
	</div>
</div>



{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<button class="button fill:white elevate button-grow:5 border-radius:round color:grey-d1 margin-bottom:2">Button</button>
<button class="button fill:blue elevate button-grow:5 border-radius:round margin-bottom:2">Button</button>

<div class="padding:2 fill:white border-radius elevate margin-bottom:4">
	<div class="row:media row-gutter:1">
		<div class="column">
			<img src="https://pbs.twimg.com/profile_images/803356024690216960/CH3i813s_400x400.jpg" class="media border-radius:round media-size:5 fill:primary elevate">
		</div>
		<div class="column display:flex align-item:middle">
			<div>
				<p class="margin:none font-weight:medium color:black font-height:0">Jin Park</p>
				<span class="font-size:tiny font-height:0">@zapcss</span>
			</div>
		</div>
	</div>
</div>
```
{{% /codeblock %}}

##### Options

The following modifiers are available.

<table class="table width:100% table:pile table@sm:unpile">
  <thead>
    <tr>
      <th>
        Property
      </th>
      <th>
        Modifier
      </th>
      <th>
        Responsive
      </th>
      <th>
        Description
      </th>
    </tr>
  </thead>
  <tr>
    <td data-label="Properties">
      <code>distribute-[axis]</code>
    </td>
    <td data-label="Attributes">
      <code>:1</code> ... <code>:5</code>
    </td>
    <td data-label="Responsive">
      Yes
    </td>
    <td class="row:reverse">
      Distribute child elements horizontally or vertically
    </td>
  </tr>
</table>
