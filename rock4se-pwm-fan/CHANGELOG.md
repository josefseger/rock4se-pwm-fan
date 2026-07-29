# Changelog

## 1.1.4

- Fixed the documentation reference on the app information page.
- Replaced the unsupported relative `DOCS.md` link with instructions to use
  the built-in Documentation tab.

## 1.1.3

- Restored the complete `run.sh` from the working 1.1.1 installation.
- Fixed `exec /run.sh: exec format error`.
- Launches the startup script explicitly through `/bin/sh`.
- Normalizes accidental CRLF line endings during the Docker build.

## 1.1.2

- First public GitHub release.
- Packaged as a public Home Assistant app repository.
- Restored and verified the working ARM64 runtime from version 1.1.1.
- Added explicit Alpine base image.
- Restricted the app to AArch64 systems.
- Preserved direct RK3399 PWM register control.
