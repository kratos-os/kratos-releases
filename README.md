# KRATOS — Official Releases

> **Closed-Source Binary Distribution Channel**
> KRATOS is proprietary software. This public repository distributes **only official signed release binaries, cryptographic SHA-256 checksums, and release metadata manifests** — no application source code is published here.

## Download Latest Android Release

- **Direct APK (Latest):** [`kratos-latest.apk`](https://github.com/kratos-os/kratos-releases/releases/latest/download/kratos-latest.apk)
- **SHA-256 Checksum:** [`kratos-latest.apk.sha256`](https://github.com/kratos-os/kratos-releases/releases/latest/download/kratos-latest.apk.sha256)
- **Version Manifest:** [`version.json`](https://github.com/kratos-os/kratos-releases/releases/latest/download/version.json)
- **Web App & Official Portal:** [kratos-os.online](https://kratos-os.online)

---

## Verify Integrity (SHA-256)

Before sideloading any APK manually, verify that its SHA-256 hash matches `kratos-latest.apk.sha256`:

### Windows (PowerShell)
```powershell
Get-FileHash .\kratos-latest.apk -Algorithm SHA256
Get-Content .\kratos-latest.apk.sha256
```

### Linux / macOS
```bash
sha256sum -c kratos-latest.apk.sha256
# or on macOS:
shasum -a 256 -c kratos-latest.apk.sha256
```

All in-app OTA updates downloaded inside KRATOS verify the Android package signature, ZIP/APK header, and SHA-256 checksum automatically prior to handing off to the Android PackageInstaller.
