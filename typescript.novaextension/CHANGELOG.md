# Changelog

## v2.3.0

### Added

- Pre-populate Rename Symbol palette with current value ([#133](https://github.com/apexskier/nova-typescript/issues/133))

## v2.2.0

### Added

- "Format Document" command

### Fixed

- Configure correct formatting before organizing imports

### Changed

- Upgrade bundled TypeScript

## v2.1.1

### Changed

- Update bundled language server with crash fix

## v2.1.0

### Added

- "Organize Imports" command
- Global/workspace preference to automatically organize imports on save

### Changed

- Upgrade bundled TypeScript

## v2.0.1

### Fixed

- Handle language server crashes more gracefully

## v2.0.0

### Fixed

- Fix paths cleaning in search results sidebar

### Breaking

- Remove functionality now supplied by Nova directly (Go to Definition, Code Action, Offer Suggestions)

## v1.8.2

### Fixed

- Fix bad bundled dependency location

## v1.8.1

### Fixed

- Fix issue with dependency installation locking during failures

## v1.8.0

### Changed

- Major behind the scene changes to dependency management
  - Performance improvements
  - More reliability with multiple open workspaces

### Fixed

- Use full completion result in manual auto-suggest command

## v1.7.0

### Added

- Support disabling processing on javascript files

### Fixed

- Display global tsserver path configuration in UI

### Changed

- Display error message with more details when activation fails
- Documentation updates

## v1.6.2

### Changed

- Removed stub language syntax
- When using bundled TypeScript, don't emit npm update checks

## v1.6.1

### Changed

- Remove confirmation/documentation message from "Offer Suggestions"

## v1.6.0

### Added

- Add "Find References" command
- Add experimental "Offer Suggestions" command

### Changed

- Auto activates in javascript workspaces
- Search results now opened by double clicking instead of selecting
- Find Symbol now uses builtin nova images for types of symbols
- Search results UI cleanup

### Fixed

- Properly dispose of more resources when extension reloads

## v1.5.3

### Changed

- Add extension to "Completions" category

### Fixed

- Fix error message when symbol can't be found
- Fix async startup failures not being logged

## v1.5.2

Mistakenly released from dev branch.

## v1.5.1

### Changed

- Emit install errors in dev console
- Upgrade bundled typescript
- Add mock typescript syntax (https://dev.panic.com/panic/nova-issues/-/issues/1454)

## v1.5.0

### Changed

- Improve documentation in readme and throughout extension
- Sidebar "refresh" button now restarts language server

### Added

- Custom TypeScript library location support (now actually works!)
- Preference type changed to string
- Relative path support
- Auto-restart on preference change

## v1.4.2

### Changed

- Upgrade bundled version of TypeScript to 3.9

## v1.4.1

### Changed

- New sidebar icons from [Sam Gwilym](http://gwil.co)

## v1.4.0

### Added

- Add images to sidebar

### Changed

- Dev functionality and error handling

## v1.3.0

### Added

- Show "Go to Definition" results in sidebar for multiple results

### Fixed

- Allow "Code Actions" and "Go to Definition" when editor doesn't have focus.

## v1.2.1

### Fixed

- Fix tsx/jsx language support

## v1.2.0

### Added

- Display active TypeScript version to sidebar
- Improved "Find Symbol" sidebar UI
- Extension falls back to it's own installation of TypeScript

### Fixed

- Fewer warnings about misconfigured TypeScript

### Changed

- Configuration for custom TypeScript installation has changed
- Language server isn't bundled with published extension

## v1.1.0

### Added

- "Find Symbol" command and sidebar
- "Code Actions" editor command
- Support for language server driven edits

### Fixed

- Cleaner deactivation logic

## v1.0.1

### Fixed

- Fix issue preventing language server startup when installed from extension library

## v1.0.0

Initial release

- Language Server support
- Custom TypeScript installation support
- "Go to Definition" editor command
- "Rename" editor command
