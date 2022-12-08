# rust-release-checklist

Checklist for releasing software written in the [Rust](https://www.rust-lang.org) programming language.

Each of the following items may assist with ensuring general correctness and quality:

1. [`cargo-test`](https://doc.rust-lang.org/cargo/commands/cargo-test.html) - Unit and integration testing.
2. [`cargo-audit`](https://github.com/rustsec/rustsec/tree/main/cargo-audit) - [Crate security vulnerability](https://rustsec.org/advisories/) auditing.
3. [`Clippy`](https://github.com/rust-lang/rust-clippy) - Linting.
4. [`cargo-fuzz`](https://github.com/rust-fuzz/cargo-fuzz) - Fuzzing.
5. Security review, as appropriate.
   * [ANSSI](https://www.ssi.gouv.fr/en) Secure Rust guide. ([web](https://anssi-fr.github.io/rust-guide), [repository](https://github.com/ANSSI-FR/rust-guide))
   * [OWASP](https://owasp.org) Top 10. ([web](https://owasp.org/www-project-top-ten), [repository](https://github.com/OWASP/Top10))
6. [`rustfmt`](https://github.com/rust-lang/rustfmt) - Formatting.
7. [`cargo-udeps`](https://github.com/est31/cargo-udeps) - Identify unused dependencies.
8. [`cargo-verify-project`](https://doc.rust-lang.org/cargo/commands/cargo-verify-project.html) - Crate manifest verification.
