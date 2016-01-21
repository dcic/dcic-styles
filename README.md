# BD2K-LINCS DCIC Styles
Within this repository are a set of styles for use across BD2K-LINCS DCIC tools and web applications.

## Palette
###Base Palette
<h1 align="center">
 <img width="600" src="https://cdn.rawgit.com/dcic/dcic-styles/master/dcic-palette.svg" alt="BD2K-LINCS DCIC" />
 <br />
</h1>
###Secondary colors for icons/accents
####Red
[Link to Hex and Colors](http://paletton.com/#uid=1020u0klcrubyGFgUv-pDo6sPj8)
<table class="color-table">
	<tbody><tr>
		<th>Primary color:</th>
		<td class="sample sample-1 primary-1">
			<div class="white">#FFA8A3</div>
			<div class="black">#FFA8A3</div>
		</td>
		<td class="sample sample-2 primary-2">
			<div class="white">#FC7D77</div>
			<div class="black">#FC7D77</div>
		</td>
		<td class="sample sample-0 primary-0">
			<div class="black">#DB514A</div>
		</td>
			<div class="white">#DB514A</div>
		<td class="sample sample-3 primary-3">
			<div class="white">#C02E26</div>
			<div class="black">#C02E26</div>
		</td>
		<td class="sample sample-4 primary-4">
			<div class="white">#98160F</div>
			<div class="black">#98160F</div>
		</td>
	</tr>
</tbody></table>

####Green
[Link to Hex and Colors](http://paletton.com/#uid=12T0u0kw0dimAmOr9i5HJ8CSi4l)
<table class="color-table">
	<tbody><tr>
		<th>Primary color:</th>
		<td class="sample sample-1 primary-1">
			<div class="white">#28893E</div>
			<div class="black">#28893E</div>
		</td>
		<td class="sample sample-2 primary-2">
			<div class="white">#116D25</div>
			<div class="black">#116D25</div>
		</td>
		<td class="sample sample-0 primary-0">
			<div class="white">#005012</div>
			<div class="black">#005012</div>
		</td>
		<td class="sample sample-3 primary-3">
			<div class="white">#00340B</div>
			<div class="black">#00340B</div>
		</td>
		<td class="sample sample-4 primary-4">
			<div class="white">#001A06</div>
			<div class="black">#001A06</div>
		</td>
	</tr>
</tbody></table>

####Purple
[Link to Hex and Colors](http://paletton.com/#uid=14I0u0kgDrR6OKgbEy2lhmTq1id)

<table class="color-table">
	<tbody><tr>
		<th>Primary color:</th>
		<td class="sample sample-1 primary-1">
			<div class="white">#C4A8D3</div>
			<div class="black">#C4A8D3</div>
		</td>
		<td class="sample sample-2 primary-2">
			<div class="white">#9B73AF</div>
			<div class="black">#9B73AF</div>
		</td>
		<td class="sample sample-0 primary-0">
			<div class="white">#7B4B94</div>
			<div class="black">#7B4B94</div>
		</td>
		<td class="sample sample-3 primary-3">
			<div class="white">#602D7A</div>
			<div class="black">#602D7A</div>
		</td>
		<td class="sample sample-4 primary-4">
			<div class="white">#481661</div>
			<div class="black">#481661</div>
		</td>
	</tr>
</tbody></table>

## Installing
You may include the dcic styles in your project in three different ways:

Add the link below within the `<head></head>` tags of your HTML file:
 ```HTML
 <link type="text/css" rel="stylesheet" href="https://cdn.rawgit.com/dcic/dcic-styles/master/dcic.min.css">
 ```

Via [bower](http://bower.io/):
```
bower install dcic-styles
```

Via [npm](https://www.npmjs.com/):
```
npm install dcic-styles
```

## CSS
The CSS file contains various styling based on the [BD2K-LINCS DCIC webpage](http://lincs-dcic.org). It also makes use of [Normalize.css](https://necolas.github.io/normalize.css/) to *"make browsers render all elements more consistently and in line with modern standards."* You may view the _base.scss or base.less files to see the CSS added in addition to the Normalize.css file.

## SASS/SCSS
If your project is using [Sass/Scss](http://sass-lang.com/), you may download the files within the sass directory of this repository and include them directly in your project.

## Less
Similarly, if you decide to use [Less](http://lesscss.org/) in your project, the files within the less directory can be downloaded and included.
