# Changelog

All notable changes to this project are recorded here.

Format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).
Versioning follows [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [Unreleased]

### Added

- Initial release: `prefs/` fragments for Java 25 compiler compliance with `--release`, autosave
  every 20 seconds, line numbers, spaces for tabs at width 4, current line highlight, spell
  checking in `en_GB` and 15 VS Code style key bindings
- `apply.sh` for macOS and Linux and `apply.ps1` for Windows, which back up a workspace's settings,
  merge the keys without touching any other line and refuse to run while Eclipse is open
- `theme/` with the eight Zacess Eclipse themes from Zacess Themes 0.3.0, tab outlines for the two
  Deep Contrast themes and an outline stylesheet for the Dark theme on macOS. The scripts import
  Zacess Deep Contrast Dark by default and take `--theme` or `-Theme` for another
- `apply.ps1` lists PowerShell 7 in the Terminal view's local shells
- `plugins.txt` listing WakaTime and its update site
- Setup and reference guides with the Eclipse Temurin 25 install line for each platform
- `ACCESSIBILITY.md` covering autosave, spell checking and the key bindings
- CI that checks the fragments, shellchecks and test-runs the merge script twice and parses the
  PowerShell script, plus markdown lint
