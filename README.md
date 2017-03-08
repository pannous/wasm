# WebAssembly 
The new bytecode for the internet

You are probably looking for [***webassembly***](https://github.com/WebAssembly/design) on github.
Or on [wiki](https://en.wikipedia.org/wiki/WebAssembly) or on [HackerNews](https://hn.algolia.com/?query=webassembly&sort=byPopularity&prefix&page=0&dateRange=all&type=story)

The whole purpose of this repository is to save you one more Google search;
  it can be removed once github creates an alias webasm->webassembly ;)

Play an [**impressive demo**](http://webassembly.org/demo/AngryBots/) of native wasm in your browser now.
Or a new [even more impressive demo](https://s3.amazonaws.com/mozilla-games/ZenGarden/EpicZenGarden.html) if you have a fast machine.

To generate binary wasm yourself, see [binaryen](https://github.com/WebAssembly/binaryen), [wabt](https://github.com/WebAssembly/wabt) or [emscripten](https://github.com/kripken/emscripten). Soon you can just use your default clang to compile c to wasm (right now you need the latest versions of llvm/lcc to do so)!

WebAssembly is *not* a binary bytecode format for standard js. 
There are reasons against overly specialized [bytecode](http://www.2ality.com/2011/01/what-is-javascript-equivalent-of-java.html). However all browsers could and should come with a compressed javascript AST reader. Someone please specify the 'jast' file format.

Compile [Ruby](http://ruby.dj/), [Python](https://github.com/replit/repl.it), C++ -> LLVM -> [asm.js](https://en.wikipedia.org/wiki/Asm.js) -> binary.wasm and load it with native speed in current(!) browsers, or in old browsers via polyfill.
