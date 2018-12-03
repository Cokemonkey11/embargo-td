# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
### Changed
- Pre-round duration reduced back down to 50.
- Multiboard widths cleaned up a bit.
- Collision circles adjusted to hopefully maintain fly-height.

## [0.2.2] - 2018-11-26
### Changed
- Attempt to fix creep-attacking issue by adding map-wide visibility for creeps.
- Reduce boss hit points from 700% to 650%.
- Time between waves reduced back down to 55.

## [0.2.1] - 2018-11-26
### Changed
- Adjusted night rounds to not start from the 1th round.
  There are still 4 night rounds.
- Towers now have slightly stronger night sight radius to fix an issue.
- Time between waves reduced back down to 60.
- The next-round timer now only begins after all creeps are killed or removed.
- Smart-locking units together now only works for owned units.
- Reduced boss HP from 800% to 700%.

## [0.2.0] - 2018-11-25
### Added
- Boss rounds.
- Night rounds.
- Wave information multiboard.
- Upgrade hotkeys.
- Automatically attach units feature.

### Changed
- Reduced Fortified armor damage reduction.
- Reduced creep collision size to prevent attacking.
- Barracks are now invulnerable.
- New map preview thanks for Frotty.

## [0.1.1] - 2018-11-20
### Changed
- Increased the round duration.
- Reduced early creep health.
- Attempted bugfix for creeps that rampage attacking players.

## [0.1.0] - 2018-11-20
### Added
- Defender with Magic attack type.
- Defender with Siege attack type.
- Map preview image.
- Collision size indicators.

### Changed
- Creeps now retry moving if they attack.
- Reduced difficulty again.
- Higher level melee and ranged defenders obtained by upgrade.
- Simplified training layout with cheapest unit first.
- Simplified and improved clarify of spawn fx.
- Reduced creep collision size.

## [0.0.2] - 2018-11-18
### Added
- A README.
- Indications of where creeps move.
- Getting started (quests menu).

### Changed
- Reduced difficulty further.

## [0.0.1] - 2018-11-18
### Added
- Improve balance to be a bit easier.
- Enclose spawns to make it more obvious where to maze.

## [0.0.0] - 2018-11-18
### Added
- Initial public test.

[Unreleased]: https://github.com/Cokemonkey11/embargo-td/compare/0.2.1...HEAD
[0.2.1]: https://github.com/Cokemonkey11/embargo-td/compare/0.2.0...0.2.1
[0.2.0]: https://github.com/Cokemonkey11/embargo-td/compare/0.1.1...0.2.0
[0.1.1]: https://github.com/Cokemonkey11/embargo-td/compare/0.1.0...0.1.1
[0.1.0]: https://github.com/Cokemonkey11/embargo-td/compare/0.0.2...0.1.0
[0.0.2]: https://github.com/Cokemonkey11/embargo-td/compare/0.0.1...0.0.2
[0.0.1]: https://github.com/Cokemonkey11/embargo-td/compare/0.0.0...0.0.1
[0.0.0]: https://github.com/Cokemonkey11/embargo-td/commit/a2411423350cbdec7013e822a266bee9248939c1
