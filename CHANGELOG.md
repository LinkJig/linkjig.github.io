# Changelog

All notable changes to LinkJig. The format follows [Keep a Changelog](https://keepachangelog.com/),
versions follow [Semantic Versioning](https://semver.org/).

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
