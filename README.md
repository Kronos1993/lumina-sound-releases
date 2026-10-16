# Lumina Sound — desktop downloads

Installers for **Lumina Sound**, a music and podcast player for your local library, by Kronos Tech.

Get the latest version from [Releases](https://github.com/Kronos1993/lumina-sound-releases/releases/latest), or from the download page at [kronos1993.github.io](https://kronos1993.github.io/lumina-sound/).

| Platform | File |
|---|---|
| macOS (Apple Silicon) | [`Lumina-Sound-macOS-arm64.zip`](https://github.com/Kronos1993/lumina-sound-releases/releases/latest/download/Lumina-Sound-macOS-arm64.zip) |
| Windows (x64) | [`Lumina-Sound-Windows-x64.msi`](https://github.com/Kronos1993/lumina-sound-releases/releases/latest/download/Lumina-Sound-Windows-x64.msi) — also on the Microsoft Store |

## Installing on macOS

1. Unzip the file and drag **Lumina Sound.app** into **Applications**.
2. Open it. macOS says it can't verify the developer, because the app isn't notarized by Apple.
3. Open **System Settings → Privacy & Security**, scroll down to the Lumina Sound message, and click **Open Anyway**.

If that option doesn't appear, run this once in Terminal:

```
xattr -dr com.apple.quarantine "/Applications/Lumina Sound.app"
```

## Installing on Windows

1. Run the `.msi`.
2. If Windows SmartScreen shows "Windows protected your PC", click **More info → Run anyway**. The installer isn't code-signed, which is why Windows shows this.

The Microsoft Store version installs without this warning.

## Premium

Lumina Sound is free. A one-time Premium unlock is available at [kronostech.lemonsqueezy.com](https://kronostech.lemonsqueezy.com/checkout/buy/9f69d6a1-1f38-4188-a94d-49a0b48d95c1).

This repository only hosts installers; it contains no source code.
