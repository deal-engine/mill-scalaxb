# Changelog

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## 0.7.0

- Upgrade to mill 0.11.6
- Upgrade to scala 2.13.12
- Upgrade to scalaxb 1.12.0

## 0.6.0

- Upgrade to mill 0.10.0

## 0.4.1

### Changed

- The scalaxb compiler is now run in a forked jvm
  instead of running in the same process as mill.

- You can customize the scalaxb dependency by
  overriding `scalaxbIvyDeps`


## [0.4.0]

### Changed
- Upgrade mill to 0.7.x and Scala 2.12.11

## [0.3.0]

### Changed
- Upgrade scalaxb to 1.7.3

## [0.2.0]

### Changed
- Upgrade mill to 0.6.x

## [0.1.0] - 2019-06-27

### Changed
- Upgraded to Mill 0.4.1 and Scala 2.12.8

## [0.0.4] - 2018-11-20

### Added
- This CHANGELOG file

### Changed
- Upgrade to Mill 0.3.5
- Use `os-lib` instead of `ammonite.ops._`
- Make build time versions easier to manage.
  Scala and mill versions are managed from `.tool-versions` file.
  The VERSION specifies this project's version number.

[Unreleased]: https://github.com/vic/mill-scalaxb/compare/0.4.1...HEAD
[0.4.1]: https://github.com/vic/mill-scalaxb/compare/0.3.0...0.4.1
[0.4.0]: https://github.com/vic/mill-scalaxb/compare/0.3.0...0.4.0
[0.3.0]: https://github.com/vic/mill-scalaxb/compare/0.2.0...0.3.0
[0.2.0]: https://github.com/vic/mill-scalaxb/compare/0.1.0...0.2.0
[0.1.0]: https://github.com/vic/mill-scalaxb/compare/0.0.4...0.1.0
[0.0.4]: https://github.com/vic/mill-scalaxb/compare/0.0.3...0.0.4
