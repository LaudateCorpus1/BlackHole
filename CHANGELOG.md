#  BlackHole Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).


### In Progress

- Add support for additional virtual formats. 24bit, 16bit.
- Sync BlackHole audio clock with any audio device.
- Create multi-output / aggregate device with installer.


## [0.2.10] - Unreleased
- Fix latency for higher values [in progress]
- sound playing through mpd is choppy [in progress]


## [0.2.9] - 2021-1-27
### Changed
- Fix clock bug. Fixes issues with BlackHole crashing on Apple Silicon.

## [0.2.8] - 2020-12-26

### Added
- Support for Apple Silicon

### Changed
- Set deployment target to 10.9. 
- Fixed bug where there is a loud pop when audio starts.
- Fix bug that caused crashes in certain situations. Issue#206
- Disable Volume and Mute controls on input. They are only needed on the output. 
- Fix clock bug.
- Automatically change UIDs to include the number of channels. Makes it easier to build and install multiple versions. Ex: BlackHole2ch_UID


## [0.2.7] - 2020-08-08
### Changed
- Improved Logarithmic Volume Control
- Various updates to README. 

### Added
- Added IOMutex to IO operations

## [0.2.6] - 2020-02-09
### Changed
- Fixed BlackHole buffer allocation error when switching audio devices from DAW.
- Fixed BlackHole buffer allocation error when sleeping.
- Audio Midi Setup speaker configuration now saves preferences.

## [0.2.5] - 2019-11-29
### Changed
- Set default volume to 1.0

## [0.2.4] - 2019-11-28
### Added
- Ability to mute and changed volume on input and out of BlackHole. 

## [0.2.3] - 2019-11-22
### Changed
- Display number of channels in audio source name.

## [0.2.2] - 2019-10-02
### Fixed
- Fixed bugs when multiple devices are reading and writing simulaniously.


## [0.2.1] - 2019-09-30
### Changed
- Set deployment target to macOS 10.10 to include Yosemite and Sierra

## [0.2.0] - 2019-09-29
### Added
- Support for 88.2kHz, 96kHz, 176.4kHz and 192kHz
- Sums audio from mutiple sources
- Changelog
- Device Icon

## [0.1.0] - 2019-09-27
### Added
- Ability to pass audio between applications
- Support for 16 channels of audio
- Support for 44.1kHz and 48kHz
