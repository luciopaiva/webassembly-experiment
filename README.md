
# WebAssembly canvas experiment

Simple WebAssembly experiment based on [this good tutorial](https://blog.scottlogic.com/2018/04/26/webassembly-by-hand.html).

This first approach defines a function that just returns a constant value.

To build it:

    node compile-save-and-run

It will automatically run the compiled code, asserting that it worked.

---

Online IDE for WebAssembly (with WAT support): [WebAssembly Studio](https://webassembly.studio/)

---

References:

- _Writing WebAssembly By Hand_ article source code: https://github.com/ColinEberhardt/wasm-game-of-life/blob/master/main.wat
- Update canvas from wasm using Rust: https://www.hellorust.com/demos/canvas/index.html
- Online IDE for C to WASM: https://wasdk.github.io/WasmFiddle/?uhvxz
