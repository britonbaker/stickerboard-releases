# Stickerboard

A small clipboard roll for your Mac.

This repository hosts official app downloads and the in-app update feed. Stickerboard's application source is private.

## Install

Download the app ZIP from [Releases](https://github.com/britonbaker/stickerboard-releases/releases), unzip it, and move **Stickerboard.app** into **Applications** before opening it.

The initial preview is for **Apple silicon Macs running macOS 14 or later**.

## Updates

After installing an updater-enabled build, use **Check for Updates…** in Stickerboard's menu. You can also allow automatic update checks when prompted. Updates are downloaded and installed by the app; there is no need to revisit GitHub or replace the app manually.

The update feed is:

`https://github.com/britonbaker/stickerboard-releases/releases/latest/download/appcast.xml`

Public release archives are signed. The update signing key stays on the release Mac; only its public key is included in the app. Clipboard contents are not sent to this repository or the update feed.

If you have an older build without an updater, install an updater-enabled build once. Future updates can then arrive inside Stickerboard.
