# Mercy Releases

Public binary distribution for Mercy.

## Version 2.0.3

- Platform: macOS ARM64
- Package: `Mercy-2.0.3-macos-arm64.dmg`
- App bundle: `Mercy.app`
- Build type: internal test build
- Signing: unsigned and not notarized
- Source: private repository; source code is not included here

This release includes the login route fix, owner-managed advertisements bundled from source, empty media-model catalogs until the matching image/video key is configured, two independently configurable key inputs for text/image/video model groups, the `BEIHAI Token 统一网关` account heading, and the Mercy brand update. The desktop data path is fixed to `~/Library/Application Support/beihstudio/data`.

This is a test build for local evaluation. It is not a formal production release and does not claim native code protection, Apple notarization, or production distribution readiness.

## Install

1. Download the DMG from the latest GitHub Release.
2. Open the DMG.
3. Drag `Mercy.app` into `Applications`.
4. On first launch, if macOS blocks the unsigned app, use **System Settings → Privacy & Security → Open Anyway**.

## Integrity

See `SHA256SUMS.txt` for the package checksum.

## Previous Versions

Versions 2.0.1 and 2.0.2 remain available from their GitHub Releases.
