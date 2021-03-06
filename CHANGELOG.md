# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.7.0] - 2020-04-26
### Added
- Support for linear sampling
- Support for `ETC1_RGB` with sRGB sampling via `RGB_ETC2_SRGB`
- Support for `ETC2_EAC_R11` and `ETC2_EAC_RG11` (there's no interface yet to explicitly choose one- or two-channel textures)

## [0.6.0] - 2020-03-01
### Added
- Support for mip-map levels
### Changed
- Updated KTX library (now at KTX 2.0 specification draft 18)

## [0.5.0] - 2020-02-22
### Added
- Support for Universal Windows Platform (not verified/tested myself)
### Changed
- `TextureBase.LoadBytesRoutine` is public now to allow deeper integration
### Fixed
- Ensured backwards compatibility with Unity 2018.2

## [0.4.0] - 2019-11-10
### Changed
- Renamed project to KtxUnity
- Using less memory by freeing up texture after GPU upload
### Added
- Support for loading KTX 2.0 files with Basis Universal super-compression

## [0.3.0] - 2019-06-30
### Added
- Thread support via Unity Job system
- Support for Android armeabi-v7a and x86

## [0.2.0] - 2019-06-25
### Added
- Support for Linux 32/64 bit

## [0.1.0] - 2019-06-23
### Added
- Added support for Windows 32/64 bit
- Docs on how to use it

### Changed
- Restructured project to be a valid Unity package

## [0.0.1] - 2019-06-21
### Added
- Changelog. All previous work was not versioned.
