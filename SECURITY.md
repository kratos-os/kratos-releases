# Security & Binary Integrity Policy

## Official Distribution Sources

Only install KRATOS Android builds distributed from:
- Official GitHub Releases: `https://github.com/kratos-os/kratos-releases/releases`
- Official Web Portal & Verified CDN: `https://kratos-os.online`

## Cryptographic Verification

Every release publishes:
- `kratos-latest.apk`: Signed release Android package (`com.hamza.kratos_app`)
- `kratos-latest.apk.sha256`: Exact SHA-256 digest of the APK binary
- `version.json`: Structured release metadata (`version`, `build_number`, `tag`, `sha256`, `size_bytes`, `released_at`)

## Reporting Security Issues

If you discover a vulnerability or suspect a tampered binary, please contact:
**Email:** `kratos.os.online@gmail.com`

Do not open public issues with exploit details.
