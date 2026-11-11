# HukStrator releases

Windows builds of **HukStrator**, a vector illustration app. This repository holds the published
installers and portable builds only; download them from
[Releases](https://github.com/awarereal/hukstrator-releases/releases/latest). HukStrator's built-in
updater checks this page for new versions and installs them.

| File | What |
|---|---|
| `hukstrator-<version>-windows-x64.msi` | Installer. Choose "Only for me" (no administrator permission, `%LOCALAPPDATA%\Programs\HukStrator`) or "Everyone" (`C:\Program Files\HukStrator`). |
| `hukstrator-<version>-windows-x64-portable.zip` | Portable build: unzip anywhere and run `HukStrator.exe`; its settings stay in `HukStratorData` beside it. |
| `SHA256SUMS.txt` | SHA-256 checksum of each file. |

If a build is not code-signed, Windows SmartScreen may show a warning the first time
("More info" › "Run anyway").

## Licence

HukStrator is licensed under the MIT License or the Apache License 2.0, at your option. It is based on
VectorCraft, Copyright (c) 2026 ArtCraft Team and the VectorCraft contributors, and is not affiliated
with or endorsed by them. Each download includes `LICENSE-MIT`, `LICENSE-APACHE`, `NOTICE` and the
third-party licences.
