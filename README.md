# WebAssembly 
The bytecode for the internet

You are looking for [webassembly on github](https://github.com/WebAssembly/design)
 on [TechCrunch](http://techcrunch.com/2015/06/17/google-microsoft-mozilla-and-others-team-up-to-launch-webassembly-a-new-binary-format-for-the-web/) or on [HackerNews](https://hn.algolia.com/?query=webassembly&sort=byPopularity&prefix&page=0&dateRange=all&type=story) << WebAssembly, webasm, wasm, webass

WebAssembly is NOT what you want if you want binary js. 
There are reasons against overly specialized [bytecode](http://www.2ality.com/2011/01/what-is-javascript-equivalent-of-java.html) but all browsers could easily come with a compressed AST reader. Someone please specify the 'jast' file format.

The whole purpose of this repository is to save you one more Google search;
  it can be removed once github creates an alias webasm->webassembly ;)

Huge drawback: asm.js (currently) is designed as a target for languages that manually manage memory allocation and release -- like C/C++. It cannot currently handle languages with garbage collection semantics, silly as that may seem given that it is JavaScript which is a garbage collected runtime.

Compile [Ruby](http://ruby.dj/), [Python](https://github.com/replit/repl.it), C++ -> LLVM -> [asm.js](https://en.wikipedia.org/wiki/Asm.js) -> binary.wasm and load it with native speed in future browsers, or in current browsers via polyfill.
You can [start playing with webassembly TODAY](https://github.com/pannous/polyfill-prototype-1)
