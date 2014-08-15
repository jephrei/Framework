#Framework v0.2&alpha;
This is a personal framework. Things will be ugly and/or [broken](http://motherfuckingwebsite.com). The final scope isn't fully realized yet, but I have my ideas. I'll probably get distracted along the way. Because this is alpha there are notes to myself and you everywhere. It's kinda messy in there.

http://jephrei.github.io/Framework/

##Another framework?
Yes. It's an unorganized pile of foo but it's mine and I'm enjoying myself. You should make one too.

##Basics Ideas
* Consitency rather than resets
* Semantic classes
* Modular design for multiple use cases (trying not to assume too much)
* Keeping it simple, stupid

##Key Features
###Implemented
* Includes normalize.css v3.0.0
* Border box model
* Responsive grid/elements
* Basic element styles

###To Do
* Flexbox - when something more stable is decided on
* Cross-browser testing
* Minified Version - after alpha most likely
* Vertical rhythm tweaks

###Maybe
* Grid increments (like 4 columns for desktop and 2 for mobile)
* Split CSS to multiple files
* Basic Form validation
* Mobile reveal menu
* Minimal animations
* LESS version (when my LESS knowledge gets better)
* toggle class (needs js)

##Compatibility
I noticed that IE7 and below sucks but you probably knew that.

There are some small bugs in IE8:
* sub pixel widths aren't supported so the ends of columns may be a pixel off from each other
* media queries aren't supported so the hide/show functionality won't trigger

##Credits
* normalize.css http://necolas.github.io/normalize.css/

##Author
[Jephrei](http://github.com/jephrei)

##License
The MIT License (MIT)

Copyright (c) 2014 Jephrei

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
