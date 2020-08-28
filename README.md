# Getting started 
`$ cargo install wasm-pack`\
`$ wasm-pack build --target web --out-name wasm --out-dir ./static`\
`$ cargo +nightly install miniserve`\
`$ miniserve ./static --index index.html`
