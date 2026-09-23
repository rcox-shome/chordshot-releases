# ChordShot for Mac

Select an area. Take a screenshot or record a silent video.

**[Download ChordShot 1.3.0 beta](https://github.com/rcox-shome/chordshot-releases/releases/tag/v1.3.0)**

Requires **macOS 15.2 or newer**. The universal app includes Apple silicon and Intel executables; Intel hardware testing is pending. The app and installer are Developer ID signed and notarized by Apple.

## Install

Download the `.dmg`, open it, and drag ChordShot into Applications. Open it there and use the two Enable… buttons to grant Accessibility and Screen Recording in System Settings. If macOS requests it, quit and reopen the same Applications copy. ChordShot stays in your menu bar when you close Settings.

## Capture

- **Mouse:** hold left + right together, drag an area, and release.
- **Trackpad:** hold Control + Option, then click-drag with one finger. Settings also offers Option alone.
- **Video:** press Space while selecting, then release. A countdown starts, followed by a red REC timer. Click Stop or press Command–Shift–X to save a silent MP4.
- **Cancel:** Escape cancels the selection or countdown.

Screenshots copy to the clipboard and save as PNG by default. Captures save to `~/Pictures/ChordShot`; videos go into its Recordings subfolder. Change the destination and output preferences in Settings. Video selection must stay within one display.

## Updates and privacy

Use **Check for Updates…** from the menu bar, or enable automatic update checks in Settings. Updates are cryptographically signed and wait for active captures to finish before restarting. Keep one installed copy in Applications. Existing development-build users may need one final permission approval when moving to the public signing identity; macOS controls all privacy access.

Captures stay on your Mac. No microphone audio, system audio, analytics, or account is used. The updater contacts GitHub to check/download releases; it never uploads captures. [Privacy details](PRIVACY.md).

## Beta feedback

This initial beta needs more real-world mouse, trackpad, multi-display, recording, and clean-install testing. Automated tests and signing checks do not replace hardware testing. [Report a problem](https://github.com/rcox-shome/chordshot-releases/issues), including macOS version, Mac model, input device, and what happened. Avoid including private screen content.

This repository contains downloads and update metadata. Application source is maintained separately in a private repository. No purchase or account is required for this beta download.
