# WASM simplest way

## Compile and run a simple program
```
$ emcc hello.c -s WASM=1 -o hello.html
$ emrun --no_browser --port 8080 .
```
Once the HTTP server is running, you can open it in your browser. If you see “Hello, world!” printed to the Emscripten console, then congratulations! You’ve successfully compiled to WebAssembly!