# RustyEx 🦀

> [!WARNING]
> _The complete repository (and my thesis) will remain private until the paper describing the tool has been published._

**My bachelor thesis:**
an instrumented `rustc` that performs [static analysis](https://en.wikipedia.org/wiki/Static_program_analysis?oldformat=true) on Rust crates to extract information about the interactions between [`cfg` features](https://doc.rust-lang.org/cargo/reference/features.html) contained in the codebase.
The goal is to determine the importance of each feature, to generate the most important configurations of features to test in the context of [SPLs](https://en.wikipedia.org/wiki/Software_product_line).
