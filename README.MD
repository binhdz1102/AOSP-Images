# AOSP-Images

Prebuilt AOSP emulator images prepared for sharing through GitHub.

## Automotive MySystemApp image

- Build date: 2026-08-02
- Product: `sdk_car_mysystemapp_x86_64-trunk_staging-userdebug`
- Android: 17 (Baklava)
- ABI: `x86_64`
- Image: Automotive AVD containing the current `My-System-App` build,
  `app_icon.png` application icon, and the privileged-permission allowlist fix
  required for a clean `system_server` boot.
- Original ZIP SHA-256:
  `ecc041491abb2eee0a2a2b8297e34b9c9544fbac718618d029452c3fab891479`
- The archive is split into 11 volumes, each below 100 MB, for GitHub upload:
  `sdk-repo-linux-system-images.7z.001` through
  `sdk-repo-linux-system-images.7z.011`.

### Restore the image

Place all 11 volumes in one directory, then run:

```bash
7z t sdk-repo-linux-system-images.7z.001
7z x sdk-repo-linux-system-images.7z.001
```

The extracted file is `sdk-repo-linux-system-images-automotive-mysystemapp-v2.zip`.
