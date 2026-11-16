# Mercy Releases

Public binary distribution for Mercy.

## Version 2.0.17

- Platforms: macOS ARM64, Windows x64
- Packages: `Mercy-2.0.17-macos-arm64.dmg`, `Mercy-2.0.17-windows-x64-Setup.exe`
- App bundle: `Mercy.app`
- Build type: internal test build
- Signing: macOS app bundle is ad-hoc signed but not notarized; Windows installer is unsigned
- Source: private repository; source code is not included here

This release includes the verified three-image Muse video-reference flow, the startup-animation rendering fix, branded Mercy installer names, and the macOS complete-bundle signing fix. The desktop data path remains `~/Library/Application Support/beihstudio/data`.

The macOS bundle has a complete ad-hoc signature, so a downloaded copy should show the standard unidentified-developer prompt instead of being reported as damaged. It still cannot open without the macOS security confirmation because the build has no Apple Developer ID or notarization ticket.

This is a test build for local evaluation. The application core is still delivered as a Bun/JavaScript bundle; this release does not claim native machine-code protection, Apple notarization, Windows Authenticode signing, or formal production distribution readiness.

## Install

### macOS

1. Download the DMG from the latest GitHub Release.
2. Open the DMG and drag `Mercy.app` into `Applications`.
3. On first launch, if macOS identifies the developer as unverified, use **System Settings → Privacy & Security → Open Anyway**.

### Windows

1. Download and run the setup executable.
2. If SmartScreen warns about an unknown publisher, choose **More info → Run anyway** after verifying the checksum below.

## Integrity

See `SHA256SUMS.txt` for all installer and update-package checksums.

## Previous Versions

Versions 2.0.14 and earlier remain available from their GitHub Releases.
