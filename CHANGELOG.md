# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [4.3.0] - tbd
### Changed
- Remove legacy syntax constructs using `pyupgrade --py38-plus`

### Fixed
- The Mongo Python driver did refactor the `gridfs` implementation, so that the patched code had to
  be adapted.

## [4.2.0] - 2024-09-11
### Changed
- Switch to [hatch](https://hatch.pypa.io) as build system.
- Switch to [PEP 621](https://peps.python.org/pep-0621/) compliant project setup.
- Updated the license to [ISC](https://en.wikipedia.org/wiki/ISC_license).

### Removed
- The [setuptools](https://setuptools.pypa.io) specific files e.g. `setup.cfg` and `setup.py` have
  been removed in the scope of the switch to `hatch`.
- Remove support for deprecated Python versions (everything prior to 3.8)


[4.3.0]: https://github.com/mongomock/mongomock/compare/4.2.0...4.3.0
[4.2.0]: https://github.com/mongomock/mongomock/compare/4.1.3...4.2.0