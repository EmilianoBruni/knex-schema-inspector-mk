# Changelog

All notable changes to this project will be documented in this file.

## [3.1.1] - 2025-08-21

### Added

- Support for combined (composite) primary keys in [`primary`](README.md#primarytable-string-promisestring--string--null).

### Changed

- Moved to pnpm

### Fixed

- Fix detection of foreign keys in CockroachDB where always returned pk of first table
- Update library to latest
- Fix Github action

## [3.1.0] - 2023-10-23

### Added

- Add support for better-sqlite3.

### Changed

- MySQL Optimization

## [3.0.1] - 2023-01-30

### Fixed

- Fix CrDB auto-increment detection ([#135](https://github.com/knex/knex-schema-inspector/issues/135))
