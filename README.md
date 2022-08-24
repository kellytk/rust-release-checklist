# rust-release-checklist

Checklist for releasing software written in the [Rust](https://www.rust-lang.org) programming language.

Each of the following assist with ensuring general correctness and quality:

1. [`cargo-test`](https://doc.rust-lang.org/cargo/commands/cargo-test.html) - [Unit](https://wikipedia.org/wiki/Unit_testing) and [integration](https://wikipedia.org/wiki/Integration_testing) [testing](https://wikipedia.org/wiki/Software_testing).
2. [`cargo-audit`](https://github.com/rustsec/rustsec/tree/main/cargo-audit) - [Crate](https://rustsec.org/advisories/) [security vulnerability](https://wikipedia.org/wiki/Vulnerability_(computing)) [auditing](https://wikipedia.org/wiki/Code_audit).
3. [`Clippy`](https://github.com/rust-lang/rust-clippy) - [Linting](https://wikipedia.org/wiki/Lint_(software)).
4. [`cargo-fuzz`](https://github.com/rust-fuzz/cargo-fuzz) - [Fuzzing](https://wikipedia.org/wiki/Fuzzing).
5. [`rustfmt`](https://github.com/rust-lang/rustfmt) - Formatting.
6. [`cargo-verify-project`](https://doc.rust-lang.org/cargo/commands/cargo-verify-project.html) - Crate manifest verification.
