# Changelog

All notable changes to XAD will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [unreleased]

### Added

### Changed

### Deprecated

### Removed

### Fixed

## [1.2.0] - 2023-05-24

### Added

-   More CI/CD workflows for all supported compiler versions
-   Added math function `copysign` 

### Changed

-   Revamped documentation site using mkdocs
-   Improved tests and testing infrastructure 

### Fixed

-   Throw exception when no tape is set on `derivative` calls
-   Some test errors with GCC versions not previously tested

## [1.1.0] - 2022-11-17

### Added

-   QuantLib integration by means of the [quantlib-xad](https://github.com/auto-differentiation/quantlib-xad) integration module
-   Full MacOS support
-   Better CI pipeline with more platforms and compilers tested
-   Code coverage and quality measured on pull requests and reported in [README.md](README.md)
-   More tests to improve code coverage
-   Status badges in [README.md](README.md)
-   Documentation updates

### Changed

-   Code quality improvements
-   Better use of caching in CI/CD pipelines for faster builds

## [1.0.0] - 2022-07-07

Initial open-source release

[unreleased]: https://github.com/auto-differentiation/XAD/compare/v1.2.0...HEAD

[1.2.0]: https://github.com/auto-differentiation/XAD/compare/v1.1.0...v1.2.0

[1.1.0]: https://github.com/auto-differentiation/XAD/compare/v1.0.0...v1.1.0

[1.0.0]: https://github.com/auto-differentiation/XAD/releases/tag/v1.0.0
