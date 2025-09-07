# ls-rs

A tiny Rust CLI that lists files and folders in a given path and displays them in a colorful, nicely formatted table.

## Features
- Path argument (defaults to current directory)
- Detects entry type (File/Dir)
- Shows file size in bytes
- Colorized, rounded table output

## Getting Started

### Prerequisites
- Rust and Cargo installed: `https://rustup.rs`

### Install dependencies
If starting from scratch, add the required crates:
```bash
cargo add clap --features derive
cargo add owo-colors
cargo add strum --features derive
cargo add tabled --features derive
```

### Build
```bash
cargo build
```

### Run
```bash
# List current directory
cargo run --

# List a specific path
cargo run -- /path/to/dir
```

## Project Structure
- `src/main.rs`: CLI entrypoint and table rendering
- `Cargo.toml`: crate configuration

## License
MIT
