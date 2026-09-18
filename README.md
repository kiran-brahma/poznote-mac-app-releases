# Poznote macOS Releases

Download the latest public Poznote for Mac developer beta:

- [Poznote for Mac v0.1.2](https://github.com/kiran-brahma/poznote-mac-app-releases/releases/tag/mac-v0.1.2)
- [Direct Apple Silicon DMG download](https://github.com/kiran-brahma/poznote-mac-app-releases/releases/download/mac-v0.1.2/Poznote-for-Mac_0.1.2_aarch64.dmg)

The beta targets Apple Silicon Macs running macOS 13 or newer. Verify the SHA-256 checksum in the release assets before opening the installer.

v0.1.0 remains available in the [release history](https://github.com/kiran-brahma/poznote-mac-app-releases/releases).

This beta is an independently distributed, ad-hoc-signed artifact. It is not Apple Developer ID signed or notarized. Install v0.1.2 manually once; subsequent signed updater checks are available from the app's Mac app row in Settings. If macOS blocks the first launch, right-click the app in Finder and choose Open.

## Upstream project and credit

This distribution packages and extends [Poznote](https://github.com/timothepoznanski/poznote), an open-source note-taking platform maintained by [Timothée Poznanski](https://github.com/timothepoznanski). The upstream project is distributed under the [MIT License](https://github.com/timothepoznanski/poznote/blob/main/LICENCE).

The macOS wrapper, packaging, release automation, and custom features are independent work. The upstream maintainer does not endorse or operate this distribution.

The upstream `LICENCE` file, `ATTRIBUTIONS.md`, provenance, checksums, and release notes are included with each published release. v0.1.2 packages upstream baseline `upstream-6.87.0` at commit `4e0a84b75af2150e5bcc5ca79dbc79fedb55e943`.

## Releases

Each release identifies the exact upstream Poznote version or commit used for the build and documents migration, recovery, signing, and update limitations.
