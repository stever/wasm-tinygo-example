# wasm-tinygo-example

WebAssembly example using [TinyGo](https://tinygo.org/getting-started/install/).

```bash
go run main.go
```

Recompiling the `main.wasm` file:

```bash
tinygo build -o html/main.wasm -target wasm html/main.go
```

Based on example provided by Aaron Turner and licensed under the
[Creative Commons Attribution 4.0 License](https://creativecommons.org/licenses/by/4.0/).