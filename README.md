# Relicbound TD — Releases

Downloadable builds of **Relicbound TD**. The game source is kept in a separate
private repository; only finished builds are published here.

## Getting the game

Download `RelicboundTD-vX.Y.Z-win64.zip` from the
[latest release](../../releases/latest), unzip it anywhere inside your user
folder, and run `RelicboundTD.exe`.

Windows 10 or 11, 64-bit. There is nothing to install.

> The download is not code-signed, so Windows may warn about it the first time.
> Right-click the ZIP, choose **Properties**, tick **Unblock**, then **OK** —
> before extracting it.

Avoid unzipping into Program Files; the updater runs without administrator
rights and will not be able to write there.

## Updates

You only ever download by hand once. From v1.1.2 onwards the game checks this
page when it starts, and if there is a newer build it offers to install it, then
restarts itself. Your saves, unlocks and settings are not affected.

If you have no internet connection the game starts normally and says nothing.

## What each release contains

| File | Purpose |
|---|---|
| `RelicboundTD-vX.Y.Z-win64.zip` | The game itself |
| `RelicboundTD-vX.Y.Z-win64.zip.sha256` | Checksum for the ZIP above |
| `manifest.json` | Read by the in-game updater |

## Reporting a problem

Please include the version number, shown on the Changelog panel of the main
menu. If an update failed, the updater log inside your game folder says why.