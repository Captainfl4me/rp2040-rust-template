# Template to build a RP2040 RUST project

This repos should be use with [cargo-generate](https://cargo-generate.github.io/cargo-generate/index.html) to create a template from it.

## Requirements

In order to be able to compile the code you will need the thumbv6m-none-eabi target and elf2uf2-rs. Find the install command below:

```
rustup target add thumbv6m-none-eabi
cargo install elf2uf2-rs
```
