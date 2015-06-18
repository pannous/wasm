# WebAssembly 
The bytecode for the internet

You are looking for [webassembly on github](https://github.com/WebAssembly/design)
 on [TechCrunch](http://techcrunch.com/2015/06/17/google-microsoft-mozilla-and-others-team-up-to-launch-webassembly-a-new-binary-format-for-the-web/) or on [HackerNews](https://hn.algolia.com/?query=webassembly&sort=byPopularity&prefix&page=0&dateRange=all&type=story) << WebAssembly, webasm, wasm, webass

The whole purpose of this repository is to save you one more Google search;
  it can be removed once github creates an alias webasm->webassembly ;)

Huge drawback: asm.js (currently) is designed as a target for languages that manually manage memory allocation and release -- like C/C++. It cannot currently handle languages with garbage collection semantics, silly as that may seem given that it is JavaScript which is a garbage collected runtime.

Compile [Ruby](https://github.com/opal/opal), [Python](https://github.com/replit/repl.it), C++ -> LLVM -> [asm.js](https://en.wikipedia.org/wiki/Asm.js) -> binary.wasm and load it with native speed in future browsers, or in current browsers via polyfill.
You can [start playing with webassembly TODAY](https://github.com/pannous/polyfill-prototype-1)
