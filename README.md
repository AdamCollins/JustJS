# JustJS
<img src="logo.png" alt="alt text" width="420px">
> A lightweight library that allows you to get back to JavaScript's basics by just being JavaScript.

[![Build Status][travis-image]][travis-url]

JustJS is the world's lightest JavaScript library, providing no more functionality than JavaScript already offers, as JustJS is **just JavaScript**. Our team decided not to improve JavaScript's ugly syntax, poor performance or, its overall low usability in large scale applications in the name of not giving front-end developers another "goddamn JavaScript library learn".

## Compatibility
* AngularJS
* ReactJS
* JQuery.js
* P5.JS
* Underscore.js
* Backbone.js
* Ember.js
* LiterallyAnything.js

## Setup
### npm install
```
npm install just.js
```
Include in document
```html
<script type="text/javascript" src="node_modules/just.js/just.js"></script>
```
### Manual install
Place the JustJS folder into your sites home directory.
Add the following line into the head of your HTML document.
```html
<script type="text/javascript" src="JustJS/just.js"></script>
```
Voilà! You have are now ready to use JustJS.
To begin, use JavaScript as you would normally as JustJS adds absolutely **NO** functionality! 
## Usage example

Here is an example of how to run a simple `Hello World!` program.

```html
<!DOCTYPE html>
<html>
<head>
	<title>Testing JustJS</title>
	<!--Step 1) include JustJS-->
	<script type="text/javascript" src="JustJS/just.js"></script>
	<style type="text/css">body{background-color: #191919; color:#FFF;}</style>
</head>
<body>
	<h1 id="title"></h1>
</body>
	<!--Step 2) Use Javascript as normal-->
	<script type="text/javascript">
		document.getElementById("title").innerHTML = "<center>Hello World with JustJS!</center>";
	</script>
</html>
```

For a more indepth reference on how to use JustJS checkout a comprehensive guide [here](https://www.w3schools.com/js/default.asp).

## License
Distributed under the ISC license.


[npm-image]: https://img.shields.io/npm/v/datadog-metrics.svg?style=flat-square
[npm-url]: https://npmjs.org/package/datadog-metrics
[npm-downloads]: https://img.shields.io/npm/dm/datadog-metrics.svg?style=flat-square
[travis-image]: https://img.shields.io/travis/dbader/node-datadog-metrics/master.svg?style=flat-square
[travis-url]: https://travis-ci.org/dbader/node-datadog-metrics
