# Changelog

All notable changes to LinkJig. The format follows [Keep a Changelog](https://keepachangelog.com/),
versions follow [Semantic Versioning](https://semver.org/).

## [1.0.4] - 2026-11-19

### Added
- Undo: deleted rows, Clear and Ctrl+L can be undone for 8 seconds.
- Module pages open the serial dialog at the module's speed.

### Changed
- Phones: search has its own row, the keyboard no longer opens on its own, hex rows fit narrow
  screens, and the log can be saved from the phone menu.
- Search keeps the match in view, also sideways when lines are not wrapped.

### Fixed
- Very long logs save, wrap and recover without freezing the app.
- Bluetooth LE: a line split over several notifications stays in one row.
- Faster with long logs on Windows when no screen reader is running.
- Android devices without Wi-Fi can install the app again.

## [1.0.3] - 2026-11-08

### Added
- Modules: ready-made commands and a health check for your device, starting with ESP8266.
- Copy on select on the desktop: dragging over terminal lines copies them (on by default, can be
  turned off in Settings).
- Crash reports are kept on your device; you decide whether to send one.

### Changed
- Two-finger font size on phones follows your fingers and applies when you let go.

### Fixed
- A crash with USB HID devices on Windows; serial connections close more safely.
- Joining a device's Wi-Fi network on Android 9, and reconnecting when a network comes back.
- Languages the app does not offer now open in English.
- New installs no longer show the update notes.

## [1.0.2] - 2026-10-30

### Fixed
- Wi-Fi/TCP: automatic reconnect joins the module's Wi-Fi first, then opens TCP; a manual Connect
  always works, also while an automatic attempt is running.
- No freeze when the font size changes on a full terminal.
- Clear while scrolled up; triggers without Pro now say why they did not run; HID time deltas.

### Added
- Settings → Send feedback with a diagnostic report.
- Terminal colors, session sharing, response time after a send, scenario run history.
- Desktop: Ctrl+A selects all rows (Delete clears), shortcuts work wherever the focus is,
  the selected and connected device is marked; option to clear the terminal on a new link type.

## [1.0.1] - 2026-10-18

- First public release on the Microsoft Store; Google Play closed test.
- Desktop: the Google Play link stays hidden until the Android app is public.

## [1.0.0] - 2026-10-16

- First build, Google Play internal test only.
