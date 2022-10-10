# rust-release-checklist

Checklist for releasing software written in the [Rust](https://www.rust-lang.org) programming language.

Each of the following items may assist with ensuring general correctness and quality:

1. [`cargo-test`](https://doc.rust-lang.org/cargo/commands/cargo-test.html) - [Unit](https://wikipedia.org/wiki/Unit_testing) and [integration](https://wikipedia.org/wiki/Integration_testing) [testing](https://wikipedia.org/wiki/Software_testing).
2. [`cargo-audit`](https://github.com/rustsec/rustsec/tree/main/cargo-audit) - [Crate](https://rustsec.org/advisories/) [security vulnerability](https://wikipedia.org/wiki/Vulnerability_(computing)) [auditing](https://wikipedia.org/wiki/Code_audit).
3. [`Clippy`](https://github.com/rust-lang/rust-clippy) - [Linting](https://wikipedia.org/wiki/Lint_(software)).
4. [`cargo-fuzz`](https://github.com/rust-fuzz/cargo-fuzz) - [Fuzzing](https://wikipedia.org/wiki/Fuzzing).
5. Security review, as appropriate.
   * [ANSSI](https://www.ssi.gouv.fr/en) Secure Rust guide. ([web](https://anssi-fr.github.io/rust-guide), [repository](https://github.com/ANSSI-FR/rust-guide))
   * [OWASP](https://owasp.org) Top 10. ([web](https://owasp.org/www-project-top-ten), [repository](https://github.com/OWASP/Top10))
6. [`rustfmt`](https://github.com/rust-lang/rustfmt) - Formatting.
7. [`cargo-udeps`](https://github.com/est31/cargo-udeps) - Identify unused dependencies.
8. [`cargo-verify-project`](https://doc.rust-lang.org/cargo/commands/cargo-verify-project.html) - Crate manifest verification.
