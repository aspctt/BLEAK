# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.3.0] - 2026-10-18

### Added

- Vesper and Vesper - Editor profiles, a softer grade with lighter desaturation, warm highlights and moderate bloom
- Editor versions of Umia and Everon

### Changed

- Umia and Everon auto exposure is darker
- Everon has stronger chromatic aberration
- Rounded off the profile values

### Removed

- Motion blur from Umia and Everon, since it caused problems with volumetric clouds

### Fixed

- Borealis brightness and ambient occlusion radius had no effect in the modes it uses, and are removed
- Everon tone curve settings had no effect with the ACES tonemapper, and are removed
- Borealis auto exposure minimum and maximum were the wrong way round

## [1.2.2] - 2026-09-30

### Changed

- Needs KSP 1.9 or later, as TUFX does, and is marked compatible up to 1.12.x
- The changelog follows Keep a Changelog and is now `CHANGELOG.md`
- Rewritten README, with a description of each profile

### Fixed

- KSP-AVC's changelog link pointed to a file that didn't exist

## [1.2.1] - 2024-11-17

### Added

- A KSP-AVC version file
- A NOTICE file with copyrights and trademarks

### Changed

- The download includes the full GPL 3.0 license text

## [1.2.0] - 2023-10-26

### Added

- Borealis and Borealis - Editor profiles

## [1.1.0] - 2022-12-12

### Added

- Everon profile

### Fixed

- Naming issues

## [1.0.0] - 2022-12-06

First release, with the Umia profile.

[Unreleased]: https://github.com/aspctt/BLEAK/compare/1.3.0...HEAD
[1.3.0]: https://github.com/aspctt/BLEAK/compare/1.2.2...1.3.0
[1.2.2]: https://github.com/aspctt/BLEAK/compare/1.2.1.0...1.2.2
[1.2.1]: https://github.com/aspctt/BLEAK/compare/1.2...1.2.1.0
[1.2.0]: https://github.com/aspctt/BLEAK/compare/1.1...1.2
[1.1.0]: https://github.com/aspctt/BLEAK/compare/1.0...1.1
[1.0.0]: https://github.com/aspctt/BLEAK/releases/tag/1.0
