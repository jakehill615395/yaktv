# YakTV downloads

**Downloader code: 6382073**

Enter the number in Downloader on your Fire TV, then install the APK as an update.

- [Direct Fire TV APK](https://github.com/jakehill615395/yaktv/releases/latest/download/YakTV-FireTV.apk)
- [Downloader short link](https://aftv.news/6382073)
- [Release notes, checksums and third-party notices/source archives](https://github.com/jakehill615395/yaktv/releases/latest)

Current release: **YakTV 0.10.0 preview**. Original player for Android TV and Android-based Fire TV. Each person signs in with their own provider account; no viewing account or channels are supplied.

This update improves decoder handoff, repeated UHD opens, background video-surface recovery and automatic blank-video fallback. Channel zapping uses cached provider/category order. Branding appears while the library loads; guide refresh runs in the background. Search is compact in the header and poster rows scroll fully into view.

Physical AFTKRT Fire TV testing passed 30 consecutive synthetic UHD opens, three native VLC background returns, four native close/reopens and 120 injected remote channel presses without restarting the process. The 30-open test sampled 97.6–123.2 MiB PSS. Provider streams, HDR/audio and prolonged thermal endurance remain outside this synthetic qualification.

The same signed package upgrades earlier YakTV/Lounge TV releases and retains compatible app data. ARMv7 and ARM64 are included. Android API 26+ is required; Fire OS 6 and Vega OS are unsupported.

Provider availability and codec support vary. The supplied provider presets use HTTP; obtain the provider's supported HTTPS address for protected login transport.

Published APK SHA-256:

```
818e13e1a82ee24ec8e57217cfe06695aefcba38b04937da7d3bc9db1854fc45
```

The release contains unmodified libVLC SDK binaries. Licence notices and pinned corresponding native source archives are attached. YakTV is an independent player.
