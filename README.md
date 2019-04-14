# Go Wasm Example

This is a minimal example of running Go in the browser.

```sh
# 
cp "$(go env GOROOT)/misc/wasm/wasm_exec.js" .
GOOS=js GOARCH=wasm go build -o main.wasm main.go
```