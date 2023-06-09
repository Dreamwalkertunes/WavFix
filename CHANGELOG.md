# Changelog

All notable changes to the WavFix project will be documented in this file.

## [Unreleased]

### Planned

- Create a unique and improved icon for the application
- Linux support
- Implement an updater
- Pop-out window for additional waveform analysis:
- Add functionality to inspect basic information about the WAV files

## [1.1.0] - 2023-04-26

### Added (v1.1.0)

- Color theme (dark/light mode) state saves between sessions. The setting is saved in the user config directory as a small .json file.

### Fixed (v1.1.0)

- In previous versions, whenever a call to update the color theme was made, the function to read the wav data was called. This meant that if large amounts of files were loaded when the user toggled the color theme, the program would lag. This has been fixed.

### Known Bugs (v1.1.0)

- The Main Window (ttk.Treeview) scales differently on different DPI monitors.

## [1.0.1] - 2023-04-25

### Fixed (v1.0.1)

- Minor improvement to edit_wav_file logic to optimize export efficiency.

### Known Bugs (v1.0.1)

- The Main Window (ttk.Treeview) scales differently on different DPI monitors.

## [1.0.0] - 2023-04-22

### Added (v1.0.0)

- UI consistency between platforms improved
- Minor improvements to code structure to optimize export efficiency

### Fixed (v1.0.0)

- Fixed a bug introduced in v0.2 that caused folders without a competing file name to be saved with "_clean" appended

### Known Bugs (v1.0.0)

- The Main Window (ttk.Treeview) scales differently on different DPI monitors.

## [0.2] - 2023-04-07

### Added (v0.2)

- Added support for .raw file types
- Interface improvements
- Lightmode/Darkmode feature, accessible by clicking the "By Dreamwalker" author text

### Changed (v0.2)

- Minor changes to file pathing to improve consistency between operating systems

## [0.1] - 2023-04-02

### Added (v0.1)

- Initial build of WavFix
