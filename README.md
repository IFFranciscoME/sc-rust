# sc-rust

Notes and Snippets on Scientific Computing with Rust


## Rust Notebook Kernel

Make sure using the up-to-date installation tools

```shel
rustup update
```

Clean environment and cache from any previous execution.

```shell
cargo clean && cargo install evcxr_jupyter
```

Install the Rust kernel for jupyter

```shell
evcxr_jupyter --install
```

Then just run jupyter and the `rust` kernel will be available.

```shell
jupyter notebook
```

