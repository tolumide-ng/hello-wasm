Guide from [MDN](https://developer.mozilla.org/en-US/docs/WebAssembly/Rust_to_wasm)

### Requirements
a. Install `wasm-pack` on your local machine
b. rustup

### Build the package 
```
1. wasm-pack build --target web // target web
2. wasm-pack build --target bundle // target npm
```
### Serve the root directory
```
python3 -m http.server
```
