# YakTV downloads

**Downloader code: 9041182**

Enter this number in Downloader on your Fire TV, then install the APK as an update.

- [Direct Fire TV APK](https://yaktv-download.vercel.app/YakTV.apk)
- [Downloader short link](https://aftv.news/9041182)
- [Download page and library notices](https://yaktv-download.vercel.app/)

Current release: **YakTV 0.13.0 preview**. Android 5.1/API 22 and newer are supported, including Android-based Fire OS 5 and Fire OS 6. Vega OS cannot run Android APKs. ARMv7 and ARM64 are included. The owner-signed package upgrades earlier YakTV/Lounge TV releases without clearing saved accounts.

Channel switching cancels blocked network reads before waiting for the old player to stop; cleanup survives rapid successive changes. Back from live full screen opens the channel selector, and Back again opens Home with a compact player and access to Movies/Series. Vertical remote keys navigate movie controls without seeking; horizontal keys scrub. Both players start with Best fit and black video backgrounds. Manual sizing remains available.

Automatic Thunder/XStream HTTP user-agent profiles and manual Advanced settings are retained, alongside the simple interface, explicit-click search, provider ordering, name-only channel lists and yak startup video. Each person signs into their own provider account; no viewing account or channels are supplied.

Verification: 92 JVM tests pass with no release lint errors. Signed APK installation/startup and synthetic ExoPlayer/VLC playback, repeated switches, Back navigation and complete poster rows passed on Android API 22 and 25 emulators. A separate D-pad test verifies Up/Down focus navigation without seeking and Right scrubbing. Emulator results do not qualify every physical Fire TV codec or provider stream.

**Known issues:** previous real-provider UHD timeouts, HTTP 406 refusals and VLC reopening failures are not universally qualified as fixed. Matching a user-agent header does not reproduce every provider handshake or override account/device/connection rules. Audio, HDR and prolonged playback require further physical-device qualification.

Downloads are static CDN files, with no runtime proxy or client redirect to GitHub. The retired code **6382073** remains without a working download target.

Published APK SHA-256:

```
2adad82d97fd1e13cae0602207342eeaf221e122fceee670beffb87bcfa329c4
```

[Third-party notices](https://yaktv-download.vercel.app/THIRD_PARTY_NOTICES.txt), [VLC source details](https://yaktv-download.vercel.app/LIBVLC_SOURCE.md) and [Java runtime source details](https://yaktv-download.vercel.app/DESUGAR_SOURCE.md) include the applicable licences and corresponding upstream source archives. YakTV is an independent player. Application source and account data are not published here.
