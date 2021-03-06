# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## Unreleased

## [0.1.3] - 2018-11-26

### Changed

- #77 retry transient HTTP exceptions @domenkozar
- #151 prevent mingled  store paths output @domenkozar
- #141 prevent unncessary warning about /etc/nix missing @domenkozar
- #142 ditch hpack @domenkozar

## [0.1.2] - 2018-09-27

### Changed

- #132 error handling for readProcess invocations @domenkozar
- #130 only warn about not supporting groups if user is not trusted @domenkozar
- #128 Generate https://cache.nixos.org when run as root on NixOS @yegortimoschenko
- #121 bail out if narSize is 0 @domenkozar
- #123 support passing --config @domenkozar
- #123 no more spurious warning messages when using "cachix use" @domenkozar
- #105 pass https://cache.nixos.org explicitly @domenkozar

## [0.1.1] - 2018-08-03

### Added

- #102 Nix 1.0 support @domenkozar

### Changed

- #105 Always specify cachix.nixos.org on NixOS @domenkozar
- #98, #95 Use LTS-12.X and Servant 0.14.1 @domenkozar

## [0.1.0.2] - 2018-07-06

### Changed

- #95 Upgrade to servant-0.14.1 @domenkozar

## [0.1.0.1] - 2018-07-05

### Changed

- #92 Add build-tool-depends where needed @domenkozar
- #90 HLint fixes @domenkozar
- #86 Improve Cabal description and synopsis @domenkozar
- #87 Support fsnotify 0.3.x @domenkozar

## [0.1.0.0] - 2018-07-01

### Added

- Initial release @domenkozar
