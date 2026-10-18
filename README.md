# MCL-T releases

Downloads for **MCL-T**, a Windows launcher for Minecraft: Java Edition. This repository holds only
release files; the source code is not public.

## Install

1. Open the [latest release](https://github.com/alecsxiop/mcl-releases/releases/latest).
2. Download `mcl-t-setup-X.Y.Z.exe` and run it. No administrator rights are needed; you can choose to
   install for all users in the setup wizard.

MCL-T needs Windows 10 or 11 (64-bit) and the
[.NET 10 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/10.0).

The installer is not code-signed yet, so Windows SmartScreen may warn about an unknown publisher.
Choose **More info → Run anyway** if the file came from this page.

## Files in each release

| File | Purpose |
| --- | --- |
| `mcl-t-setup-X.Y.Z.exe` | Installer for a new installation |
| `mcl-t-X.Y.Z-win-x64.zip` | Application files, used by the launcher's built-in updater |
| `SHA256SUMS.txt` | SHA-256 checksums of the two files above |

To check a download in PowerShell, compare `(Get-FileHash .\file -Algorithm SHA256).Hash` with the
matching line in `SHA256SUMS.txt`.

## Updates

Once installed, MCL-T can check this page for newer versions and update itself. Updates replace
only the application's own files - your instances, worlds, settings and accounts are never touched.

## License

Proprietary. All rights reserved. The release files may be used under the terms that accompany each
release. MCL-T is not affiliated with or endorsed by Mojang Studios or Microsoft.
