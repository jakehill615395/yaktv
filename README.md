# YakTV downloads

**Downloader code: 9041182**

Enter this number in Downloader on your Fire TV, then install the APK as an update.

- [Direct Fire TV APK](https://yaktv-download.vercel.app/YakTV.apk)
- [Downloader short link](https://aftv.news/9041182)
- [Download page and library notices](https://yaktv-download.vercel.app/)

Current release: **YakTV 0.12.0 preview**. The download is a static CDN file: no runtime proxy, per-download GitHub fetch or client redirect to GitHub. The retired code **6382073** no longer has a working download target.

Automatic HTTP user-agent compatibility profiles for Thunder and XStream are included. A manual override is available under Settings → Interface mode: Advanced → Find a setting → Network → HTTP user agent override, with playlist/channel overrides also supported. Custom values take priority over profiles and stream-supplied agents. VLC's HTTP user-agent argument is corrected. These settings change request headers, not account access or the app's package/signature.

The simpler interface, compact explicit-click search, stable poster sizing on Back, name-only channel lists, live corner preview and yak cold-launch video are retained. Accounts and interface preferences are preserved.

Verification: 86 JVM tests and four physical Fire TV synthetic playback/header workflows passed, including manual overrides in both engines. The actual Downloader code reached the YakTV install prompt on the physical stick, and the downloaded file matched the signed build. Timing includes the redirect and automation overhead. Fixture audio was disabled for the playback/header checks.

**Known issues:** real-provider UHD timeouts, HTTP 406 refusals and VLC reopening failures are not claimed fixed. Matching a user agent does not reproduce every provider handshake or override subscription/device/connection rules. Audio, HDR, every Fire TV model and prolonged playback remain incompletely qualified.

The owner-signed package `dev.loungetv.player` upgrades earlier compatible YakTV/Lounge TV releases and retains app data. Each person uses their own provider account; no viewing account or channels are supplied. ARMv7 and ARM64 are included. Android API 26+ is required; Fire OS 6 and Vega OS are unsupported.

Published APK SHA-256:

```
9313420f44fda7fed928d5235a405988b0dc50bb70660842cc799eea910f26ce
```

[Third-party notices](https://yaktv-download.vercel.app/THIRD_PARTY_NOTICES.txt), the [library licence](https://yaktv-download.vercel.app/LibVLC-LGPL-2.1.txt), [pinned source details](https://yaktv-download.vercel.app/LIBVLC_SOURCE.md) and native source archives are available through the download page. YakTV is an independent player.
