# Segue — releases

Installers and signed update files for **Segue**, the live-performance app. This repository contains release
binaries only — no source code.

- **Download:** see [Releases](../../releases) → the latest version → *Assets*.
  - macOS (Apple Silicon): `Segue_<version>_aarch64.dmg`
  - Windows (x64): `Segue_<version>_x64-setup.exe`
- **In-app updates:** installed copies of Segue (0.5.0 and later) check `latest.json` from the latest release here.
  Every update file is signed; the app verifies the signature against the public key built into it and refuses
  anything unsigned or modified.

The builds are not notarized (macOS) or code-signed (Windows): macOS may ask you to confirm opening the app,
Windows SmartScreen may warn — choose *More info → Run anyway*.
