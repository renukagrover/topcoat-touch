Topcoat Touch
=============

[![Build Status](https://travis-ci.org/kriserickson/topcoat-touch.png?branch=master)](https://travis-ci.org/kriserickson/topcoat-touch)

A very simple mobile framework based on the [Topcoat Framework](http://topcoat.io), innspired by
the [jQT](http://jqtjs.com/) framework.  Can be used either with a [single html document with multiple pages](/example/one-document/), or
using a [collection of controllers and templates](/example/mvc/).  It uses a collection of optional libraries to provide most of the functionality
 for a mobile framework:

* [jQuery](http://jquery.com) or [Zepto](http://zeptojs.com) to provide dom manipulation.
* [fastclick](https://github.com/ftlabs/fastclick) is an optional plugin to remove the 300ms click delay in [most](http://updates.html5rocks.com/2013/12/300ms-tap-delay-gone-away) mobile browsers
* [iScroll](https://github.com/cubiq/iscroll) is an optional plugin that can be used to provide smooth scrolling automatically.
* [hammer.js](http://eightmedia.github.io/hammer.js) is an optional plugin to allow TopcoatTouch to provide event brokering for mobile touch options (swipe, tap, hold, doubletap, drag, roate, pinch, etc).
* [lodash](http://lodash.com/) is a plugin that is only required when using [templating strategy](/example/mvc/), of course you could also use [underscore](http://underscorejs.org/).
    Currently the default is underscore style templates, but you can easily use [Handlebars](http://handlebarsjs.com/) or [Mustache](https://github.com/janl/mustache.js).
    See [tips and tricks](//github.com/kriserickson/topcoat-touch/wiki/Tips-Tricks) for a simple example
    using [Handlebars](https://github.com/kriserickson/topcoat-touch/wiki/Tips-and-Tricks#wiki-using-handlebars-as-the-templating-engine) or
    [Mustache](//github.com/kriserickson/topcoat-touch/wiki/Tips-and-Tricks#wiki-using-mustache-as-the-templating-engine).  You could add your own templating engines following these guidelines.

Uses some of the CSS for page flipping from the Christopher Coenraets [topcoat/backbone](http://coenraets.org/blog/2013/06/sample-mobile-phonegap-application-with-backbone-js-and-topcoat) example
and screencasts.

See the example files [index.html](/example/index.html) and [app.js](/example/js/app.js) to see how it is used.

Read more about why topcoat-touch was created on my blog post, [It Appears You are Building A Framework](http://www.agingcoder.com/2014/01/06/it-appears-like-you-are-building-a-framework/)

* [Getting Started](//github.com/kriserickson/topcoat-touch/wiki/Getting-Started) -- Getting started with topcoat touch.




