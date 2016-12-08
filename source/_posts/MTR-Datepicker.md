title: MTR-Datepicker
tags:
  - datepicker
  - javascript
  - javascript datepicker
  - js
  - js datepicker
  - library
  - mtr-datepicker
categories:
  - en
  - projects
date: 2016-12-08 18:46:00
---
---

## The pure JavaScript datepicker library

{% asset_img cover.png mtr-datepicker %}

MTR Datepicker is a library written in pure JavaScript which allows you to create great looking and lightweight datepickers for you web apps. It is supported by all of the modern internet browsers and comes with a few customizable themes.

A simple preview of the datepicker is available [here](http://mtrdesign.github.io/mtr-datepicker/demo.html). You can customize the datepicker and make it works the way you want. You can download the latest version of the datepicker and test it in your projects or play with the live demo in [jsfiddle](https://jsfiddle.net/mtr_datepicker/469qq7xv/).



# Get the code

There are two possible ways to include the mtr-datepicker library in your project. You can [download](https://github.com/mtrdesign/mtr-datepicker/archive/master.zip) the latest stable release form the [official site](http://mtrdesign.github.io/mtr-datepicker/) and include it in your templates.


Or if you prefer to be up-to-date with our latest releases with a package manager you can use [Bower](https://bower.io/) or [NPM](https://www.npmjs.com/), just type in your Terminal or CMD the following command:


```
bower install --save mtr-datepicker
```
or
```
npm install --save mtr-datepicker
```



# Load the library

First you need to load the styles of the datepicker. Put the following lines in the head section of your html file or template:

```
<link rel="stylesheet" type="text/css" href="dist/mtr-datepicker.min.css">
<link rel="stylesheet" type="text/css" href="dist/mtr-datepicker.default-theme.min.css">
```

Then you should load the JavaScript, we suggest you to put the lines at the bottom of the body section of your html file or template. That is all, now you are ready to initialize your first datepicker.

```
<script type="text/javascript" src="dist/mtr-datepicker.min.js"></script>
```




# How to use

To use the loaded scripts just add an element with specific id to your html and then tell the library to make it a datepicker. Here is a simple example:

```
<div id="first-mtr-datepicker"></div>

<script>
  var config = {
    target: 'first-mtr-datepicker'
  };
  var myDatepicker = new MtrDatepicker(config);
</script>
```

You can use more advanced datepickers and customize their behavior. You can learn more  from the [API](http://mtrdesign.github.io/mtr-datepicker/docs.html#scrollspy-api) section of the docs.




# Contribute

We will appreciate it if you want to support our project and contribute to make it better. You can read our [Contributions guide](http://mtrdesign.github.io/mtr-datepicker/docs.html#scrollspy-contribute) in the official docs or send us your ideas in the [issues tracker](https://github.com/mtrdesign/mtr-datepicker/issues).


---
date: 2016-12-08
author: Valentin Kirilov