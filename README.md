### Rust Player

Following O'Reilly's Rust Begginers course to try rust and
learn a little bit before following any of the books.
https://learning.oreilly.com/videos/rust-in-motion

> Material uses rust version 1.24.0, I am running 1.78.0.

#### Notes

- stablity gurantee, will run in any higher version with the same major version.
- IRC networks for rust supports seems to be down, discord is the way now.
- Template for gitignore file -> `https://www.toptal.com/developers/gitignore/api/rust`
- binary crates create an executable, other choices are libary crate for example.
- I won't be putting much more notes, as this short cause is to get up and running, before starting book, I will just document commands.

#### Commands

- `rustc --version`
- `cargo --version`
- `cargo new --bin ProjectName`
- cd into projectory and run commands there.
- `cargo build`
  - compiles in project directory.
  - `Cargo.lock` -> dependencies
  - `target/debug/<project_name> -> executable.
- `cargo build --release` -> prod
- build and run -> `cargo run`

#### Learning Order

- O'Reilly - Rust Video Course.

#### Environment

- Github codespaces, in vscode, run `ctrl + shift + p` then `add dev..` choose dev container configuration files.
  - Just choose the rust main one, no optional ones.
