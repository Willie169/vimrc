# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a
Changelog](https://keepachangelog.com/en/1.0.0/), and this project adheres to
[Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

   > Possibly related discussions and information
   >
   > - [GitHub -- `termux/termux-app` -- Issue `3838` -- Feature: Screen dimming in Termux settings](https://github.com/termux/termux-app/issues/3838)
   > - [GitHub -- `termux/termux-app` -- Issue `897` -- Feature request: Selectively allow termux to keep screen on](https://github.com/termux/termux-app/issues/897)
   > - [Redit -- Check if display is on or off](https://www.reddit.com/r/termux/comments/11e2s3j/check_if_display_is_on_or_off/)
   > - [Redit -- How to wake/turn on the screen via Termux?](https://www.reddit.com/r/termux/comments/kysbsk/how_to_waketurn_on_the_screen_via_termux/)

## [0.0.1] - 2024-03-26

### Added

- Start maintaining versions and a changelog.

## [0.0.2] - 2026-03-11

### Added

- Add fast finish when Termux clipboard commands are not available.
- Add `Z` mapping to get Android clipboard into unnamed reg.

### Changed

- Change yanking to use system to be more robust.
- Change `p` and `P` to not be remapped by default to be compatible with [vim-yankstack](https://github.com/maxbrunsfeld/vim-yankstack).
- Fix <https://github.com/vim-utilities/termux-clipboard/issues/1>.

### Removed

- Remove fallback since Termux build typically doesn't have clipboard support.

