custom-javascript-logger
========================

# General #

An add on to the normal javascript console.log command, which allows you to turn them off all at once with a simple line of code.

This is a direct copy of a script by [solutionyogi](http://stackoverflow.com/users/92414/solutionyogi) which can be found here: [Stackoverflow](http://stackoverflow.com/a/1215400/3352437)

This has been tested in following browsers, for all other I cannot garantuee it works:
* Google Chrome Version 37.0.2062.120
* Microsoft Internet Explorer Version 9.0.8.112.16421
* Firefox 33.1.1
 
# Usage #

* Add `logger.disableLogger();` to the ready event of the page disable all log messages
* Add `logger.enableLogger();` to the ready event of the page enable all log messages
* Add anywhere to disable for only a section `logger.disableLogger();` and add `logger.enableLogger();` to start logging again.

Please be aware that isn't doing anything to the source JS, which still will hold all the comments, they simply wont be output to the console.
