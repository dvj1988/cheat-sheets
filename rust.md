# Rust

## Install Rust
```
curl https://sh.rustup.rs -sSf | sh
```

## Check if rust is installed
```
cargo --version
rustc --version
```

## Open offline documentation
```
rustup doc
```

## Create a new Rust Project
```
cargo new <project-name>
```

## Check if the code compiles
Navigate to the root folder of the project &
```
cargo check
```
## Compile and Run
### Create executable binary
debug
```
cargo run
```
release
```
cargo run --release
