# environment requirements

```
rustup component add llvm-tools-preview
rustup target add thumbv6m-none-eabi

cargo install flip-link
cargo install open-ocd
cargo install elf2uf2-rs
cargo install cargo-binutils
```

```
cargo build --release
elf2uf2-rs target/thumbv6m-none-eabi/release/rustpi
# drag over file
```