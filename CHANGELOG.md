# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [v2.1.1] - 2022-06-15

- Restore trashed files asynchronously
- Add padding to item information UI
- Add log message if there is an error monitoring a directory

## [v2.1.0] - 2021-08-07

- Add file size to info displays (credit to brent for the idea)
- Fix file operations on trashed items failing because of permission issues (#8)
- Improve error handling and notifications
- Use different panel icons when there are no items in the trash vs when there are items (credit to Katoa for the idea)

## [v2.0.0] - 2021-06-13

- Formatting improvements to the item info revealers
- Tooltip improvements throughout the applet (more relevant, descriptive, etc.)
- Confirmation revealer text now line-wraps if it is too long
- Redesigned the settings page
- Settings are now stored in a `gschema`. You no longer have to change it back after every login!
- Timestamp labels now use locale formatting to display the date and time
- Trash bins can now be collapsed by clicking on the header
- Add placeholder text when a trash bin is empty
- Add appstream info file
- Various style changes

[unreleased]: https://github.com/EbonJaeger/budgie-trash-applet/compare/v2.1.1...master
[v2.1.1]: https://github.com/EbonJaeger/budgie-trash-applet/compare/v2.1.0...v2.1.1
[v2.1.0]: https://github.com/EbonJaeger/budgie-trash-applet/compare/v2.0.0...v2.1.0
[v2.0.0]: https://github.com/EbonJaeger/budgie-trash-applet/compare/v1.2.0...v2.0.0
