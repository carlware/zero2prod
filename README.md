## Project from the zero2prod book


# some useful tools
```shell
rustup update
brew install llvm
cargo install cargo-watch
cargo install cargo-tarpaulin
cargo clippy
cargo tarpaulin --ignore-tests
cargo clippy -- -D warnings
cargo fmt
cargo fmt -- --check
cargo audit

cargo add actix-web@4
cargo add tokio@1 --features macros,rt-multi-thread

# database
cargo install --version="~0.7" sqlx-cli --no-default-features --features rustls,postgres

# expand macros
cargo +nightly expand

# to use cargo expand
cargo install cargo-expand
rustup toolchain install nightly --allow-downgrade
```