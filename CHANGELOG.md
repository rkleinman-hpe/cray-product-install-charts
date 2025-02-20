# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [4.5.0] - 2025-02-18

### Dependencies

- CASMCMS-9282: Bump `cray-product-catalog` from 2.5 to 2.7 for CSM 1.7

## [4.4.3] - 2024-09-16

### Dependencies

- Bump `cray-product-catalog` from 2.3 to 2.5 for CSM 1.6

## [4.4.2] - 2024-07-16

### Dependencies

- Bump `cray-product-catalog` from 2.1 to 2.3 for CSM 1.6

## [4.4.1] - 2024-03-20

### Dependencies

- Bump `cray-product-catalog` from 2.0 to 2.1 for CSM 1.6

## [4.4.0] - 2024-02-08

### Dependencies

- Bump `cray-product-catalog` from 1.10 to 2.0 for CSM 1.6

## [4.3.0] - 2023-11-29

### Dependencies

- Bump `cray-product-catalog` from 1.9 to 1.10

## [4.2.0] - 2023-11-29

### Changed

- Disabled concurrent Jenkins builds on same branch/commit
- Added build timeout to avoid hung builds

### Dependencies

- Bump `actions/checkout` from 3 to 4 ([#34](https://github.com/Cray-HPE/cray-import-kiwi-recipe-image/pull/34))
- Bump `stefanzweifel/git-auto-commit-action` from 4 to 5 ([#35](https://github.com/Cray-HPE/cray-import-kiwi-recipe-image/pull/35))
- Bump `cray-product-catalog` from 1.8 to 1.9

## [4.1.0] - 2023-08-14

### Fixed

- CASMCMS-8743 - fix BOS V2 session endpoint template generation.

## [4.0.0] - 2023-05-23

### Changed

- Utilize BOS Version 2 (BOS V2) endpoint for session templates. Further, change the variable name from `BOS_SESSION_ENDPOINT` to `BOS_SESSIONTEMPLATES_ENDPOINT`.

## [3.2.0] - 2023-04-06

### Changed

- Reverted github workflows back to Jenkins pipelines.
- Finished conversion to GitVersion; modified build and versioning process to match other CMS repositories.
- Update to cray-product-catalog-update version 1.8.x

### Removed

- Removed references to import-config chart which was removed long ago.
- Removed outdated maintainers information from chart.

## [3.1.0] - 2022-08-02

### Changed

- Update license text to comply with automatic license-check tool.
- CASMCMS-7970 - update dev.cray.com addresses.

## [3.0.2] - 2022-03-04

### Changed

- Use github public ubuntu runner instead of self-hosted on public repos.

## [3.0.1] - 2022-02-17

### Added

- Include additional changes for CASMCMS-7676 (IMS templating) missed during repo conversion

## [3.0.0] - 2022-02-14

### Changed

- Converted repository to just cray-import-kiwi-recipe-image, using GH actions and workflows to build (CASMCMS-7812)

- Converted repository to CSM gitflow development process (CASMCMS-7812)

- Updated GH artifact retention to 90 days for chart

- Update to cray-product-catalog-update version 1.5.2

- Publish location changed due to update to artifactory plugin

### Removed

- Chart no longer builds via Jenkins

## [2.0.0] - 2021-11-29

### Added

- See https://github.com/Cray-HPE/cray-product-install-charts for this release and prior.

[Unreleased]: https://github.com/Cray-HPE/cray-import-kiwi-recipe-image/compare/v4.4.2...HEAD

[4.4.2]: https://github.com/Cray-HPE/cray-import-kiwi-recipe-image/compare/v4.4.1...v4.4.2

[4.4.1]: https://github.com/Cray-HPE/cray-import-kiwi-recipe-image/compare/v4.4.0...v4.4.1

[4.4.0]: https://github.com/Cray-HPE/cray-import-kiwi-recipe-image/compare/v4.3.0...v4.4.0

[4.3.0]: https://github.com/Cray-HPE/cray-import-kiwi-recipe-image/compare/v4.2.0...v4.3.0

[4.2.0]: https://github.com/Cray-HPE/cray-import-kiwi-recipe-image/compare/v4.1.0...v4.2.0

[4.1.0]: https://github.com/Cray-HPE/cray-import-kiwi-recipe-image/compare/v4.0.0...v4.1.0

[4.0.0]: https://github.com/Cray-HPE/cray-import-kiwi-recipe-image/compare/v3.2.0...v4.0.0

[3.2.0]: https://github.com/Cray-HPE/cray-import-kiwi-recipe-image/compare/v3.1.0...v3.2.0

[3.1.0]: https://github.com/Cray-HPE/cray-import-kiwi-recipe-image/compare/v3.0.2...v3.1.0

[3.0.2]: https://github.com/Cray-HPE/cray-import-kiwi-recipe-image/compare/v3.0.1...v3.0.2

[3.0.1]: https://github.com/Cray-HPE/cray-import-kiwi-recipe-image/compare/v3.0.0...v3.0.1

[3.0.0]: https://github.com/Cray-HPE/cray-import-kiwi-recipe-image/compare/v2.0.0...v3.0.0

[2.0.0]: https://github.com/Cray-HPE/cray-product-install-charts/releases