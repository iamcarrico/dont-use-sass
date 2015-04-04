## What is wrong with it?

* Long selector chains <!-- .element: class="fragment" -->
* "Invisible" in how it operates <!-- .element: class="fragment" -->
* Can't use within media queries <!-- .element: class="fragment" -->
* Not flexible <!-- .element: class="fragment" -->


Note: Hugo Giraudel's article (http://www.sitepoint.com/avoid-sass-extend/) goes into depth at what is wrong about over-using the @extend directive. It can allow for many selectors to all be used for a single rule (see: clearfix). It also acts in an invisible sort of way, without a logical way of knowing where a selector will be placed when you extend things. This causes some rules to be extending without you wanting them to be. Mostly though, it is 100% inflexible, not allowing for input to change the output.

Some samples that I use:

http://sassmeister.com/gist/e3f8e6eb925eea301a1a http://sassmeister.com/gist/ffebe27d8f8f8c43aa6d http://sassmeister.com/gist/6fc782abeb1f3722e4b4 http://sassmeister.com/gist/6080e0c363526d40c1f6 http://sassmeister.com/gist/05f5bfb5275ddcd5d2f0 http://sassmeister.com/gist/258528c84bde2fdad2da
