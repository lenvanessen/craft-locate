# Locate Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/) and this project adheres to [Semantic Versioning](http://semver.org/).

## 2.2.0 - 2022-02-24
- Fixed Composer 2 compatibility
- Compatibility PHP 8 and PHP 8.1
- Fixed compatibility with Craft > 3.5 @jasperboot

## 2.1.1 - 2019-02-27
### Fixed
- Bug where place data with emojis would prevent saving of field
- Bug where hitting enter to select a place would instead trigger a save on the entry before place was selected

## 2.1.0 - 2018-09-14
### Fixed
- Clearing a location field now *actually* removes all field data from the database :)

### Added
- The field now returns `locationData`. This is the full API response from Google.
- Returns `locationData.components` which is a keyed array of all the Google `address_components` data.

## 2.0.2 - 2018-08-09
### Fixed
- Scoped all CSS to plugin

## 2.0.1 - 2018-04-25
### Added
- Fixed incorrect repo urls

## 2.0.0 - 2018-04-09
### Added
- Initial Craft3 release

## 0.4.9 - 2016-02-18
### Added
- Initial release
