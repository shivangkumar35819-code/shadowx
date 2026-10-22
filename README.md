# ShadowX 2.0

Download SHADOW-X-v2.0.apk from this repository or the latest GitHub Release.
Install over your existing app to retain its device identity. Open it and log in once before any later uninstall/reinstall so the old HWID can migrate.

Changes:
- Download only the selected matching RT/QX driver; verify SHA-256 and size before loading; cache for reuse.
- Separate Edit buttons next to Add ShadowX and Add Night / DND.
- Online Settings, remote notices and config checks removed. Check for updates remains.
- Persistent native device identity survives reinstall; old server device slots still require the provider if the identity was already lost.

Requirements: Android 8+, ARM64 and working root. Kernel/driver compatibility varies. No universal 120 FPS unlock is included.

Validation: signed APK and 16 KB ZIP alignment verified; signer matches v1.19.1; source/regression checks passed; all 50 hosted driver files verified. No connected phone was available for live login, reboot/reinstall or kernel driver tests.

online-drivers/ contains required hosting files; do not delete them. The app pins commit 09849255b2c78b6f3f0c2e5d2b3c9056eda0d376. update.json describes this exact signed APK.
