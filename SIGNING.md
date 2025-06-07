# NekoBox Signing Information

This repository includes a public keystore for consistent APK signing across all builds.

## Keystore Details
- **File**: `release.keystore`
- **Alias**: `nekobox`
- **Password**: `nekobox2024`
- **Validity**: 100 years

## Important Notes
- This is a PUBLIC keystore intended for open-source builds only
- DO NOT use this keystore for any commercial or private projects
- All releases from this repository will use this keystore to ensure update compatibility

## Building Locally
The build scripts will automatically use this keystore. No additional configuration needed.
