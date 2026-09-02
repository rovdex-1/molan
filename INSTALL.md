# MOLAN Desktop Installation

Download installers from the [MOLAN Releases](https://github.com/rovdex-1/molan/releases)
page. Choose the package matching your operating system and CPU architecture.

## macOS

- Apple Silicon: `MOLAN-<version>-macos-arm64.dmg`
- Intel: `MOLAN-<version>-macos-x64.dmg`

Open the DMG and drag MOLAN to Applications. Packages are currently unsigned;
macOS may require Finder **Open** or approval in Privacy & Security.

## Windows

Run `MOLAN-<version>-windows-x64-Setup.exe`. SmartScreen may show an
unknown-publisher warning because Authenticode signing is not configured yet.
The Windows ZIP is available as an installation-free alternative.

## Linux

On Debian or Ubuntu, install the DEB package:

```bash
sudo apt install ./MOLAN-<version>-linux-x64.deb
```

The Linux ZIP is available for manual execution on other distributions.

## SHA-256 verification

Download `SHA256SUMS.txt` from the same release as the installer.

macOS/Linux:

```bash
sha256sum -c SHA256SUMS.txt
# macOS alternative
shasum -a 256 -c SHA256SUMS.txt
```

Windows PowerShell:

```powershell
Get-FileHash .\MOLAN-<version>-windows-x64-Setup.exe -Algorithm SHA256
```

Only install a package after its checksum matches the file listed in the same
GitHub Release.
