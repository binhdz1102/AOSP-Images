# AOSP-Images

Prebuilt AOSP emulator images prepared for sharing through GitHub.

## Automotive MySystemApp image v4

- Build date: 2026-08-22
- Product: `sdk_car_mysystemapp_x86_64`
- Android: 17 (Baklava), API 37
- ABI: `x86_64`
- Build ID: `CP2A.260605.016`
- Image: Automotive AVD containing the `MySystemApp` build and `CarSystemUI` Display Compatibility & Safe Region fix (full-screen 1920x1080 display for all 3rd-party apps).
- Original ZIP SHA-256:
  `407ed1ade99c1cd3cae8d752a21489bcde90fd9dfc780998e4b7af7cf7f795e3`
- The archive is split into 8 volumes, each below 100 MB, for GitHub upload:
  `sdk-repo-linux-system-images-automotive-mysystemapp-v4.7z.001` through
  `.008`.

### Restore the v4 image

Place all 8 v4 volumes in one directory, then run:

```bash
7z t sdk-repo-linux-system-images-automotive-mysystemapp-v4.7z.001
7z x sdk-repo-linux-system-images-automotive-mysystemapp-v4.7z.001
```

The extracted file is `sdk-repo-linux-system-images-automotive-mysystemapp-v4.zip`.
See `sdk-repo-linux-system-images-automotive-mysystemapp-v4.manifest` for
checksums and exact volume sizes.