Change Log
==========

All notable changes to this project will be documented in this file, which
follows the conventions of [keepachangelog.com](http://keepachangelog.com/).
This project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]

...

## [1.0.0] - 2015-10-29

### Added
- Hash functions now support Strings, ByteBuffers, and InputStreams in addition
  to byte arrays.
- Add `functions` map of keywords to supported hash functions.
- Add `test` function to validate a multihash against some content.

### Fixed
- Add type hints to a number of functions.

## [0.2.0] - 2015-09-26

### Added
- Add `multihash.base58` encoding functions.
- Refactor into `multihash.hex` encoding functions.
- Define a `print-method` for multihashes.
- Add support for reading a multihash from a byte stream.

### Changed
- Upgrade to clojure 1.7.0.
- Change `Multihash` fields to be prefixed with an underscore.
- Change `(:digest multihash)` to return a byte array.

### Removed
- `(:bytes multihash)` no longer returns a byte array.

## [0.1.2] - 2015-06-06

### Changed
- Rename `algorithms` map to `algorithm-codes`.
- Improve conditionals in validation functions.

## 0.1.1 - 2015-03-06

Initial project release.

[Unreleased]: https://github.com/greglook/clj-multihash/compare/1.0.0...HEAD
[1.0.0]: https://github.com/greglook/clj-multihash/compare/0.2.0...1.0.0
[0.2.0]: https://github.com/greglook/clj-multihash/compare/0.1.2...0.2.0
[0.1.2]: https://github.com/greglook/clj-multihash/compare/0.1.1...0.1.2
