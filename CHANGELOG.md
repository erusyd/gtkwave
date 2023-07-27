# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [Unreleased]

### Changed

- Merged in major GUI widget refactoring.

### Added

- Added support for `namespace import gtkwave::*` in Tcl scripts.
- Added OpenBSD and FreeBSD OS support for unbuffered FST I/O.
- Added `dbl_mant_dig_overrides` rc environment variable.

### Fixed

- Fixed toggle menu item access under Tcl.
- Path fix for twinwave on Windows.
- Fixed high CPU usage on Wayland.
- Compiler fix for __GTK_SOCKET_H__ availability.

[Unreleased]: https://github.com/gtkwave/gtkwave/compare/v3.3.116...HEAD