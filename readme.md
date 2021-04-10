![crates.io](https://img.shields.io/crates/v/safe_index.svg)
![Documentation](https://docs.rs/safe_index/badge.svg)
![CI](https://github.com/AdrienChampion/safe_index/workflows/CI/badge.svg)

# safe_index

Zero-cost-wraps `usize`-s to give them a specific type. The motivation is to have different kinds of
indices that are incompatible at type-level, thus lowering the chance of mixing them up compared to
using `usize`-s.

Index-type creation is done through a macro, so the type actually belong to the client crate. This lets users augment index-types with methods, trait implementations, *etc.*

See the [documentation] for details.

[documentation]: https://docs.rs/safe_index (safe_index's documentation)
