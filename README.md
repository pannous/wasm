# WebAssembly 
The bytecode for the internet

You are probably looking for *[webassembly](https://github.com/WebAssembly/design)* on github.
Or on [wiki](https://en.wikipedia.org/wiki/WebAssembly) or on [HackerNews](https://hn.algolia.com/?query=webassembly&sort=byPopularity&prefix&page=0&dateRange=all&type=story)

The whole purpose of this repository is to save you one more Google search;
  it can be removed once github creates an alias webasm->webassembly ;)

Play [**impressive demo**](http://webassembly.org/demo/AngryBots/) in your browser now.
http://webassembly.org/demo/Tanks/

WebAssembly is *not* a binary bytecode format for standard js. 
There are reasons against overly specialized [bytecode](http://www.2ality.com/2011/01/what-is-javascript-equivalent-of-java.html). However all browsers could and should come with a compressed javascript AST reader. Someone please specify the 'jast' file format.

Compile [Ruby](http://ruby.dj/), [Python](https://github.com/replit/repl.it), C++ -> LLVM -> [asm.js](https://en.wikipedia.org/wiki/Asm.js) -> binary.wasm and load it with native speed in future browsers, or in current browsers via polyfill.
You can [start playing with webassembly TODAY](https://github.com/pannous/polyfill-prototype-1)
