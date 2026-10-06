# Changelog

All notable changes to `swisnl/phpstan-bitbucket` will be documented in this file.

Updates should follow the [Keep a CHANGELOG](https://keepachangelog.com/) principles.

## [Unreleased]

### Added

- Support PHPStan 2.x alongside PHPStan 1.x, synchronized from upstream 0.4.0.
- Document runtime requirements and registration of both PrestaModule forks.

### Retained

- PHP 7.2 compatibility for PHPStan 1.x and bulk annotation delivery through the reports fork.


## [0.4.0] - 2025-01-31

### Added

- Added support for PHPStan 2 [#1](https://github.com/swisnl/phpstan-bitbucket/pull/1).


## [0.3.0] - 2023-12-22

### Changed

- Bumped minimum PHP version to 8.0.
- Report title is now simply "PHPStan".
- Moved several base classes to [swisnl/bitbucket-reports](https://github.com/swisnl/bitbucket-reports).


## [0.2.0] - 2022-11-04

This release lists changes compared to [alxt/phpstan-bitbucket:0.1.0](https://github.com/modprobe/phpstan-bitbucket/releases/tag/v0.1.0).

### Changed

- Bumped minimum PHP version to 7.4 and add support for PHP 8.
- Bumped dependencies.
- This error formatter will now also report errors using the default table error formatter.
- Changed package name to `swisnl/phpstan-bitbucket` and namespace to `Swis\PHPStan\ErrorFormatter`.
