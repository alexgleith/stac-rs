# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic
Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added

- Doctesting for README.md
- `Href::rebase`
- `Object` and `HrefObject`
- Architecture diagram

### Changed

- Simplified `Render`'s href creation
- CI workflows

### Fixed

- Type signature for `BestPracticesRenderer::new` to `From<Href>` (was `TryFrom<Href>`)

### Removed

- `stac::render`

## [0.0.2] - 2022-02-14

### Added

- More information to the README

### Removed

- Custom docs build

## [0.0.1] - 2022-02-14

Initial release.

[unreleased]: https://github.com/gadomski/stac-rs/compare/v0.0.2...HEAD
[0.0.2]: https://github.com/gadomski/stac-rs/compare/v0.0.1...v0.0.2
[0.0.1]: https://github.com/gadomski/stac-rs/releases/tag/v0.0.1