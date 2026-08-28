# PIC Android Updates

This public repository is the credential-free update channel for **PIC — Pilot Intelligence Companion**.

- Application source remains private in `FatumLab/Pilot-Intelligence-Companion`.
- `latest.json` is the canonical update manifest.
- `latest.sig` is a detached RSA/SHA-256 signature over the exact bytes of `latest.json`.
- Installable APK files are published as GitHub Release assets.
- The Android application accepts an APK only after manifest-signature, SHA-256, package-name, version-code and Android signing-certificate verification.

No application secrets or GitHub credentials belong in this repository or in the APK.
