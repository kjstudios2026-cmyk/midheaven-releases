# Rocket App: Windows installers

This repository holds the Windows installers for Rocket App, the ballast and
altitude calculator for TARC flights, and nothing else. The source code lives in
a separate, private repository.

## Installing

1. Open the [latest release](https://github.com/kjstudios2026-cmyk/rocket-app-releases/releases/latest)
   and download `RocketApp-Setup-<version>.exe`.
2. Run it. There is no administrator prompt: it installs for you only.
3. If Windows says *"Windows protected your PC"*, choose **More info → Run
   anyway**. The installer is not code-signed yet.

Windows 10 or 11, 64-bit. About 450 MB once installed.

## Updating

Nothing to do here. The installed app checks this page every hour, and when a
newer release is out an **Update** button appears at the top of the app on the
laptop. One click installs it; your flights, settings and backups are never
touched.

## What each release contains

- `RocketApp-Setup-<version>.exe`: the installer.
- `release.json`: what the app's Update button reads (the version, the
  installer's size and SHA-256, and what changed).

The version is the app version, then the build's date and time in UTC:
`7.2026.1003.1832` was built on 3 October 2026 at 18:32 UTC.
