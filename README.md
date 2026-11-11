# HukStrator releases

Windows builds of **HukStrator**, a vector illustration app. This repository holds the published
installers and portable builds only; download them from
[Releases](https://github.com/awarereal/hukstrator-releases/releases/latest). HukStrator's built-in
updater checks this page for new versions.

| File | What |
|---|---|
| `vectorcraft-<version>-windows-x64.msi` | Installer. Choose "Only for me" (no administrator permission, `%LOCALAPPDATA%\Programs\HukStrator`) or "Everyone" (`C:\Program Files\HukStrator`). |
| `vectorcraft-<version>-windows-x64-portable.zip` | Portable build: unzip anywhere and run `vectorcraft.exe`; settings stay in the folder. |
| `SHA256SUMS.txt` | SHA-256 checksum of each file. |

The file and program names keep the `vectorcraft` prefix of the project HukStrator is based on; the
updater relies on it.

The builds are not code-signed yet, so Windows SmartScreen may show a warning the first time
("More info" › "Run anyway").

## Licence

HukStrator is licensed under the MIT License or the Apache License 2.0, at your option. It is based on
VectorCraft, Copyright (c) 2026 ArtCraft Team and the VectorCraft contributors, and is not affiliated
with or endorsed by them. Each download includes `LICENSE-MIT`, `LICENSE-APACHE`, `NOTICE` and the
third-party licences.
