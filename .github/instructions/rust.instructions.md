---
applyTo: "**/*.rs,**/Cargo.toml,**/Cargo.lock"
---

# Rust instructions

- Use the repository's configured stable toolchain and Cargo workspace structure.
- Prefer idiomatic ownership and borrowing over unnecessary cloning; avoid `unsafe` unless the task explicitly requires it and the invariant is documented.
- Return meaningful `Result` errors instead of using `unwrap` or `expect` outside examples and tests.
- Run `cargo fmt`, `cargo clippy --all-targets --all-features -- -D warnings`, and the narrowest relevant `cargo test` command.
- Do not edit `target` or generated artifacts.
