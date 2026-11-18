# Cyberspace for Android

The Android app for [Cyberspace](https://cyberspace.online).

This repository holds signed release APKs only. Download them from [Releases](https://github.com/unremarkablegarden/cyberspace-android/releases).

## Requirements

- Android 7.0 (API 24) or later.
- Google Play services are not required. Without them, push notifications do not work. Everything else does, signup included.

## Install

1. Download `cyberspace-<version>.apk` from the latest release.
2. Open the file. Android asks you to allow installs from the app that opened it (your browser or file manager). Allow it.
3. Tap Install.

## Updates

Every release is signed with the same key, so a new APK installs over the old one and keeps your login and settings.

To get updates automatically, add this repository to [Obtainium](https://github.com/ImranR98/Obtainium):

```
https://github.com/unremarkablegarden/cyberspace-android
```

## Verify the APK

Check the signing certificate before you install:

```bash
apksigner verify --print-certs cyberspace-4.3.apk
```

The certificate SHA-256 digest must be:

```
11412080b6b8c850345c881dbdfc0a2997c98b16e16aa71f5b1a36f2794aaa51
```

If it is different, do not install the file.

## Support

Report problems on Cyberspace or at [cyberspace.online](https://cyberspace.online).
