# Changelog
This file will document changes to this project.

Unfortunately, [Semantic Versioning](https://semver.org/) is not suitable for Dwarf Fortress raw mods because too many changes would be `MAJOR` save incompatible changes, so this project uses a custom versioning convention instead; for a given version number `RELEASE.MAJOR.MINOR`, increment the:
- `RELEASE` version for updates that require a new version of DF. Not compatible with existing saves.
- `MAJOR` version for updates that are _not_ save-compatible, and thus require a new world/save file.
- `MINOR` version for updates that _are_ save-compatible, and can be applied to existing worlds/save files.

The "Unreleased" heading is for changes that are in the repo but not in any published version (they are probably not ready yet).

The meaning of each subcategory of change is as follows:
- Added: A new file, section in a file, or object was created, or a feature added to an object. If a creature ID exists but is unimplemented/has `[DOES_NOT_EXIST]` and cannot be spawned even in the testing arena, this doesn't count as being added.
- Changed: An existing file or object/property has been edited/changed. Changes that will not be recorded include most code comments inside files, updates to `CHANGELOG.md` that are simply recording other changes, or `README.md` updating the mod version or promoting something from "planned content" to "content".
- Deprecated: An object is technically present, but no longer indended to be used and will be removed soon.
- Removed: An object, property, or section of a non-raw file was deleted.
- Fixed: A bug/error or a typo was fixed. If it's a fix, it will not be recorded under any of the above headings.

## [Unreleased]

### Added

### Changed

### Deprecated

### Removed

### Fixed
- Fixed typo in the changelog; had the wrong date for v1.0.0

## [v1.0.0] - 2022-12-09
- The initial public release.

<!--Links-->
[Unreleased]: https://github.com/Crabman-DF-Mods/--------/compare/v1.0.0...HEAD
[v1.0.0]: https://github.com/Crabman-DF-Mods/--------/releases/tag/v1.0.0