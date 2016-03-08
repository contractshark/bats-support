# Change Log

All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).


## [Unreleased]

### Added

- `npm` support

### Changed

- Renamed to `bats-support`


## 0.1.0 - 2016-02-16

### Added

- Two-column key-value formatting with `batslib_print_kv_single()`
- Multi-line key-value formatting with `batslib_print_kv_multi()`
- Mixed formatting with `batslib_print_kv_single_or_multi()`
- Header and footer decoration with `batslib_decorate()`
- Prefixing lines with `batslib_prefix()`
- Marking lines with `batslib_mark()`
- Common output function `batslib_err()`
- Line counting with `batslib_count_lines()`
- Checking whether a text is one line long with
  `batslib_is_single_line()`
- Determining key width for two-column and mixed formatting with
  `batslib_get_max_single_line_key_width()`


[Unreleased]: https://github.com/ztombol/varrick/compare/v0.1.0...HEAD