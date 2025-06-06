# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

No Unreleased changes at this moment.

## [v0.3.1] - 2025-05-11

### Miscellaneous

- Rebranded to Inkdex (@celarye)

## [v0.3.0] - 2025-04-21

### Features

- Pretty print the versioning file (#4, @celarye)
- Added repository info to the commit message (#4, @celarye)
- Sorted the extensions alphabetically in both the versioning and metadata files (#4, @celarye)
- Prevented template extensions from getting added to the registry (#4, @celarye)
- Simplified repository keys in the metadata file (#4, @celarye)
- Reject extension additions which overwrite extensions from other repositories (#4, @celarye)
- The metadata file now updates on extension updates (#4, @celarye)
- Correctly log if extensions get added, updated or deleted (#4, @celarye)

### Bug Fixes

- Fixed GitHub API file size limit issue with object fetching (#4, @celarye)
- Ensured that added extensions have valid semver versions (#4, @celarye)

### Miscellaneous

- Fixed a broken link in the changelog (#4, @celarye)
- Switched to Clippy (#4, @celarye)

## [v0.2.1] - 2025-03-10

### Bug fixes

- Extension deletion fixes (#3, @Celarye)

### Miscellaneous

- Added a GitHub test workflow for pull requests (#3, @Celarye)

## [v0.2.0] - 2025-03-09

### Features

- Ensure a clean exit (exit code 0) when no extensions need updating, display a warning instead (#2, @Celarye)
- Added extension deletion support by rewriting the versioning update logic (#2, @Celarye)

### Bug fixes

- Extension duplication (#2, @Celarye)

### Miscellaneous

- General code structure improvements (#2, @Celarye)

## [v0.1.0] - 2025-02-24

### Features

- Base registry manager tool (@Celarye)
- A GitHub workflow which releases a binary of the tool on pushed tags (@Celarye)
- `action.yml` to make the tool available through a GitHub Action (@Celarye)
- GitHub Issue templates (@Celarye)
- GitHub support, security and contributing guidelines (@Celarye)

[Unreleased]: https://github.com/inkdex/registry-manager/compare/v0.3.1...HEAD
[v0.3.1]: https://github.com/inkdex/registry-manager/compare/v0.3.0...v0.3.1
[v0.3.0]: https://github.com/inkdex/registry-manager/compare/v0.2.1...v0.3.0
[v0.2.1]: https://github.com/inkdex/registry-manager/compare/v0.2.0...v0.2.1
[v0.2.0]: https://github.com/inkdex/registry-manager/compare/v0.1.0...v0.2.0
[v0.1.0]: https://github.com/inkdex/registry-manager/releases/tag/v0.1.0
