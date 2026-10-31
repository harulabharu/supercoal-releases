# SuperCoal desktop releases

Installers and update manifests for the SuperCoal desktop app, published by
the `Desktop release` workflow in the private `roastops` repository whenever a
`desktop-v*` tag is pushed there. The app checks `latest.json` on the latest
non-prerelease for updates and verifies each download against the updater
public key built into it.

Installers are unsigned until code-signing certificates are in place, so
Windows SmartScreen and macOS Gatekeeper warn on first launch.
