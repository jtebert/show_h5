# Changelog

This documents changes for each show_h5 release.

All notable changes to this project will be documented in this file.

The format is based on `Keep a Changelog <https://keepachangelog.com/en/1.0.0/>`_, and this project adheres to `Semantic Versioning <https://semver.org/spec/v2.0.0.html>`_.
## Unreleased

### Added

- Command line interface. Once installed, just run `show_h5 ...` in your terminal. (See more in README)
- Now there's a changelog

### Changed

- Prettier formatting of datasets (both data and non-data summary)
- Filename now shown at beginning of printout
- `show_data` isn't just a boolean anymore. It's "none", "some", or "all" to say how much of numpy arrays to output

### Fixed

- You can now show just a single dataset (instead of just group-level data) (previously this just broke without good reason/explanation)