# Aeros Parametrics — public release feed

This repository holds **only release binaries** for the Aeros Parametrics Windows desktop app
(the source code is private). Each GitHub Release here (`desktop-vX.Y.Z`) contains:

- `Aeros Parametrics-X.Y.Z.msi` — the per-user Windows installer
- `latest.json` — update manifest (`version`, `notes`, `msiName`, `msiUrl`, `sha256`, `size`, `published`)

The app never contacts this feed unless the user turns on **Settings → Check for updates**
(off by default). No telemetry is sent; the request is a plain anonymous HTTPS GET of
`https://github.com/kyleanthonyhuber-beep/aeros-parametrics-releases/releases/latest/download/latest.json`.
Downloaded installers are verified against the SHA-256 in the manifest before the user is asked to launch them.
