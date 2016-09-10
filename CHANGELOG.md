# Change Log
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]

### Fixed
- Fix missing parentheses around `authortype`
- Remove `authortype` when the author is omitted
- Fix `number` field format for `collection` entries
- Improve `\bibnamedash` behavior
- Improve hyperref on `\textcite` with postnote


## [2.0.1] - 2016-08-03

### Added
- Add CHANGELOG.md
- Improve hyperref links

### Changed
- Make starred commands more consistent

### Fixed
- Improve handling of repeated titles
- Improve sorting for patents
- Allow citing with shorthand


## [2.0] - 2016-07-08

### Added
- Add `abnt-numeric` style

### Removed
- Remove `biblatex`'s deprecated `\nameparts` macro

### Fixed
- Fix problem adding entries with no author
- Fix problem with patent driver


## [1.0.1] - 2016-06-07

### Fixed
- Stop repeating same authors in citations
- Improve handling of small caps
- Improve capitalization of organization fields
- Add "et al." in citations


[Unreleased]: https://github.com/abntex/biblatex-abnt/compare/v2.0.1...HEAD
[2.0.1]: https://github.com/abntex/biblatex-abnt/compare/v2.0...v2.0.1
[2.0]: https://github.com/abntex/biblatex-abnt/compare/v1.0.1...v2.0
[1.0.1]: https://github.com/abntex/biblatex-abnt/compare/v1.0...v1.0.1
