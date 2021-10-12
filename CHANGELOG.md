# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]

## [0.0.6] - 2021-10-12
### Changed
- Upgrade to `@cucumber/cucumber-expressions 14.0.0`

## [0.0.5] - 2021-10-12
### Added
- Release as ESM module

### Changed
- The `StepDocument` type now includes an `expression: Expression` field.

## [0.0.4] - 2021-09-15
### Changed
- Upgrade to `@cucumber/cucumber-expressions 13.0.1`

## [0.0.3] - 2021-09-01
### Added
- Build choices based on all values for a parameter type, across steps
([#1671](https://github.com/cucumber/common/pull/1671)
[aslakhellesoy](https://github.com/aslakhellesoy))

## [0.0.2] - 2021-07-15
### Added
- Added `suggestion` string property on `StepDocument`
([#1657](https://github.com/cucumber/common/pull/1657)
[aslakhellesoy](https://github.com/aslakhellesoy))

### Changed
- The `StepDocument` type has changed to `{ suggestion: string, segments: StepSegments }`
([#1657](https://github.com/cucumber/common/pull/1657)
[aslakhellesoy](https://github.com/aslakhellesoy))

## [0.0.1]
### Added
- First release!

[Unreleased]: https://github.com/cucumber/suggest/compare/v0.0.6...main
[0.0.6]: https://github.com/cucumber/suggest/compare/v0.0.5...0.0.6
[0.0.5]: https://github.com/cucumber/suggest/compare/v0.0.4...v0.0.5
[0.0.4]: https://github.com/cucumber/suggest/compare/v0.0.3...v0.0.4
[0.0.3]: https://github.com/cucumber/suggest/compare/v0.0.2...v0.0.3
[0.0.2]: https://github.com/cucumber/suggest/compare/v0.0.1...v0.0.2
[0.0.1]: https://github.com/cucumber/common/tree/v0.0.1
