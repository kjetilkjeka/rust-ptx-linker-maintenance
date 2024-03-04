# Rust PTX Linker Maintenance Mode
At the time of writing (2023-12-01) the original ptx-linker project is abandoned. This fork is created to add some simple fixes on top of the old project. It will only be maintained until a better alternative is in place.

## Usage
With the recent development, you should pass `-C linker=rust-ptx-linker` (use the path to `rust-ptx-linker` if it is not contained in the `PATH` envvar) to rustc to use this linker.

## Installation
The [`ptx-linker`](https://crates.io/crates/ptx-linker) crate on crates.io is abandoned and this fork will not be published under a new name. Install by pulling this git repository and run `cargo install --git https://github.com/kjetilkjeka/rust-ptx-linker-maintenance`

## Maintenance Status
This project is not being actively maintained. PRs will not be accepted other than fixing breakage to basic usage.

## Future
The usage of this crate should be completely replaced by the [embedded-linker](https://github.com/rust-lang/rust/pull/117458#issuecomment-1836359357) and this repository should be archived.

