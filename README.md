# Rust "platforms" crate

[![Latest Version][crate-image]][crate-link]
[![Docs][docs-image]][docs-link]
[![Build Status][build-image]][build-link]
![MIT/Apache 2 licensed][license-image]
[![Gitter Chat][gitter-image]][gitter-link]

[crate-image]: https://img.shields.io/crates/v/platforms.svg
[crate-link]: https://crates.io/crates/platforms
[docs-image]: https://docs.rs/platforms/badge.svg
[docs-link]: https://docs.rs/platforms/
[build-image]: https://travis-ci.org/RustSec/platforms-crate.svg?branch=master
[build-link]: https://travis-ci.org/RustSec/platforms-crate
[license-image]: https://img.shields.io/badge/license-MIT%2FApache2-blue.svg
[gitter-image]: https://badges.gitter.im/badge.svg
[gitter-link]: https://gitter.im/RustSec/Lobby

Rust platform registry: provides programmatic access to information
about valid Rust platforms, sourced from [Rust Forge].

[Documentation]

[Rust Forge]: https://forge.rust-lang.org/platform-support.html
[Documentation]: https://docs.rs/platforms/

## About

This crate provides programmatic access to information about valid Rust
platforms. This is useful for systems which document/inventory information
relevant to Rust platforms: specifically it was created for the
[RustSec Advisory Database] as a way to document and validate which Rust
platforms security advisories are applicable to.

It is not intended to be a tool for gating builds based on the current platform
or as a replacement for Rust's existing conditional compilation features:
please use those for build purposes.

[RustSec Advisory Database]: https://github.com/RustSec

## License

Licensed under either of:

 * Apache License, Version 2.0 ([LICENSE-APACHE] or https://www.apache.org/licenses/LICENSE-2.0)
 * MIT license ([LICENSE-MIT] or https://opensource.org/licenses/MIT)

at your option.

[LICENSE-APACHE]: https://github.com/RustSec/rustsec-client/blob/master/LICENSE-APACHE
[LICENSE-MIT]: https://github.com/RustSec/rustsec-client/blob/master/LICENSE-MIT

### Contribution

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you shall be dual licensed as above, without any
additional terms or conditions.