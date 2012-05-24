# ActionScript Relative Date Library

An ActionScript 3 Library for working with and generating relative date strings.

## Overview

An ActionScript 3 Library for working with and generating relative date strings (e.g. "two hours ago" instead of "Mon Jan 5 17:24:33 GMT-0700 2011").

This project was first mentioned in my blog post at http://blogs.adobe.com/charles/2011/05/relative-time-library-for-actionscript.html.

### Features

The ActionScript Relative Date Library is a simple API (a single class, really).  It takes two date objects and returns a string describing the difference in time in a human-readable form.

### Dependencies

* [as3corelib](https://github.com/mikechambers/as3corelib)

## Reference

### Usage

	var relativeTime:String = RelativeDate.getRelativeDate(firstDate, secondDate);
	var relativeTime:String = RelativeDate.getRelativeDateFromNow(someDate);

### Demo

* Live demo: http://blogs.adobe.com/charles/2011/05/relative-time-library-for-actionscript.html
* Demo source: https://github.com/charlesbihis/sandbox/tree/master/actionscript/actionscript-relative-date-demo

### Documentation

You can find the full ASDocs for the project [here](http://charlesbihis.github.com/actionscript-relative-date/docs/).

## Author

* Created by Charles Bihis
* Website: [www.whoischarles.com](http://www.whoischarles.com)
* E-mail: [charles@whoischarles.com](mailto:charles@whoischarles.com)
* Twitter: [@charlesbihis](http://www.twitter.com/charlesbihis)

## License

The ActionScript Relative Date Library is licensed under the [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).