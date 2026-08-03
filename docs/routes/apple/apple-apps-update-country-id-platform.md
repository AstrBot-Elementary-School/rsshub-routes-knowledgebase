# Apple - App Update

## Coverage
`index-only`

## Route
- Namespace: `apple`
- Namespace Name: `Apple`
- Route Path: `/apple/apps/update/:country/:id/:platform?`
- Route Name: `App Update`
- Example: `/apple/apps/update/us/id408709785`
- URL: `apple.com`
- Language: `_None_`
- Categories: `program-update, popular`
- Maintainers: `EkkoG, nczitzk`
- Source Location: `apps.ts`
- Source Module: `_None_`

## Description
::: tip
For example, the URL of [GarageBand](https://apps.apple.com/us/app/garageband/id408709785) in the App Store is `https://apps.apple.com/us/app/garageband/id408709785`. In this case, the `App Store Country` parameter for the route is `us`, and the `App id` parameter is `id408709785`. So the route should be [`/apple/apps/update/us/id408709785`](https://rsshub.app/apple/apps/update/us/id408709785).
:::

## Parameters
- `country`: App Store Country, obtain from the app URL, see below
- `id`: App id, obtain from the app URL
- `platform`: {"description": "App Platform, see below, all by default", "options": [{"label": "all", "value": "All"}, {"label": "iOS", "value": "iOS"}, {"label": "macOS", "value": "macOS"}, {"label": "tvOS", "value": "tvOS"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `apps.apple.com/:country/app/:appSlug/:id`
  - `apps.apple.com/:country/app/:id`
- `target`: `/apps/update/:country/:id`

## Raw JSON
```json
{
  "categories": [
    "program-update",
    "popular"
  ],
  "description": "::: tip\nFor example, the URL of [GarageBand](https://apps.apple.com/us/app/garageband/id408709785) in the App Store is `https://apps.apple.com/us/app/garageband/id408709785`. In this case, the `App Store Country` parameter for the route is `us`, and the `App id` parameter is `id408709785`. So the route should be [`/apple/apps/update/us/id408709785`](https://rsshub.app/apple/apps/update/us/id408709785).\n:::",
  "example": "/apple/apps/update/us/id408709785",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1551,
  "location": "apps.ts",
  "maintainers": [
    "EkkoG",
    "nczitzk"
  ],
  "name": "App Update",
  "parameters": {
    "country": "App Store Country, obtain from the app URL, see below",
    "id": "App id, obtain from the app URL",
    "platform": {
      "description": "App Platform, see below, all by default",
      "options": [
        {
          "label": "all",
          "value": "All"
        },
        {
          "label": "iOS",
          "value": "iOS"
        },
        {
          "label": "macOS",
          "value": "macOS"
        },
        {
          "label": "tvOS",
          "value": "tvOS"
        }
      ]
    }
  },
  "path": "/apps/update/:country/:id/:platform?",
  "radar": [
    {
      "source": [
        "apps.apple.com/:country/app/:appSlug/:id",
        "apps.apple.com/:country/app/:id"
      ],
      "target": "/apps/update/:country/:id"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 311841579128 to be less than 311040000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:62:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "微信是一款全方位的手机通讯应用，帮助你轻松连接全球好友。微信可以群聊、进行视频聊天、与好友一起玩游戏，以及分享自己的生活到朋友圈，让你感受耳目一新的移动生活方式。 为什么要使用微信： • 多媒体消息：支持发送视频、图片、文本和语音消息。 • 群聊和通话：组建高达500人的群聊和高达15人的实时视频聊天。 • 语音和视频聊天：提供全球的高质量通话。 • 表情商店：海量动态表情，包括热门卡通人物和电影，让聊天变得更生动有趣。 • 朋友圈：与好友分享每个精彩瞬间，记录自己的生活点滴。 • 更佳的隐私保障：微信为您提供最高级别的隐私控制权限，并已获得 TRUSTe 认证 — 查看我们的隐私政策以了解更多信息。 • 认识新朋友：通过“雷达加朋友”和“附近的人”认识新朋友。 • 实时位置共享：与好友分享地理位置，无需通过语言告诉对方。 • 多语言：支持超过20多种语言界面，并支持多国语言的消息翻译。 • 微信运动：支持接入Apple Watch及健康app数据，可在步数排行榜上和朋友一较高下。若需使用，可在“设置-通用-辅助功能”内启用。 • 更多功能: 支持跨平台、聊天室墙纸自定义、消息提醒自定义和公众号服务等。 • 关怀模式: 文字与按钮更大更清晰。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "55304675781277696",
      "image": "https://is1-ssl.mzstatic.com/image/thumb/PurpleSource221/v4/89/55/5b/89555b1d-1b1c-12bb-5dbc-707c47b52b54/Placeholder.mill/3000x3000bb.webp",
      "ownerUserId": null,
      "siteUrl": "https://apps.apple.com/cn/app/id414478124",
      "title": "微信 for iOS - Apple App Store",
      "type": "feed",
      "url": "rsshub://apple/apps/update/cn/id414478124/iOS"
    },
    {
      "description": "Ignite your video content with Infuse – the beautiful way to watch almost any video format on your iPhone, iPad, Apple TV, Mac, and Vision. No need to convert files! Infuse is optimized for visionOS 26, with powerful streaming options, Trakt sync, and unmatched subtitle support. Gorgeous interface. Precise controls. And silky-smooth playback. - PLAY MORE VIDEO TYPES A powerful video player that plays just about anything, including MP4, MKV, M4V and MOV – plus many others. Includes support for HDR, HDR10+, Dolby Vision, plus Dolby and DTS audio. - STREAM FROM OTHER DEVICES Browse and play videos stored on your Mac, PC, NAS, Wi-Fi hard drive, apps like Plex, Emby, and Jellyfin, or from cloud services like Dropbox, Google Drive, OneDrive, Box, pCloud, Yandex.Disk, MEGA, Aliyun Drive, and others – no syncing required! - TRAKT 2-WAY SYNC Connect with Trakt to sync watched history, submit ratings and post comments. - OPTIMIZED SUBTITLES POWERED BY OPENSUBTITLES Bring your own subtitles, or download them on the fly (for free) in virtually any language. ===== “Looks great, plays anything you throw at it...surprisingly powerful” - Lifehacker “The best media player for iPhone and iPad...superior to VLC.” - Cult of Mac “I can't give the UI high enough praise. It's great.” - 9to5Mac “I see no reason whatsoever to remove Infuse from my Home screen anytime soon.” - iDownloadBlog “A beautiful UI.” - Trakt co-founder “A mini Kodi!” - Infuse user ===== MORE THAN JUST A PRETTY FACE THE BASICS - Silky-smooth video player (plays full 4K w/ HDR & Dolby Vision) - Stream from a Mac, PC, NAS or Wi-Fi enabled hard drive - Connect with Plex, Emby, Jellyfin, Kodi (XBMC), WMC and other media servers - Beautiful layout with quick access to video info - Artwork and metadata added automatically - Spatial audio SUPPORTED FORMATS - Video: 33GP, AVI, AV1, ASF, BDMV, DIVX, DVDMEDIA, DVR-MS, FLV, H.264 (AVC), H.265 (HEVC), ISO/IMG, M4V, MKV, MOV, MP4, MPEG, MTS/M2TS, MXF, OGM, OGV, RMVB, TS, VC1, VIDEO_TS, VOB, VP9, WEBM, WMV, WTV - Audio: AAC, AC3/E-AC3, DOLBY TRUEHD, DTS, DTS-HD MA, FLAC, MP3, OGG, PCM, WMA - Subtitles: DVB, DVDSUB, MICRODVD, MPL2, PGS, SMI, SSA/ASS, SRT, SUB, SUP, TIMED TEXT, TMP, TXT, VOBSUB, VTT, XSUB PLAYER FEATURES - Multiple audio tracks - Chapters - Gesture controls - 8 video zoom options - Continuous playback - Deinterlacing EXTRAS - Folders - One-click subtitle downloads from OpenSubtitles - Scrobble plays to Trakt - Download videos from networked devices - Drag and drop uploads via web browser GET MORE WITH INFUSE PRO! - Play even more video formats - Stream video trailers for movies and TV shows - Enjoy high-resolution Dolby® and DTS® audio - Access videos stored in cloud services like Dropbox, Google Drive, Box, OneDrive, pCloud, Yandex.Disk, MEGA, Aliyun Drive, and more - Sync libraries, settings, watched history, and playback progress between devices ===== Note: DRM-protected movies & TV shows purchased from the iTunes store are not supported. Metadata and artwork provided by TMDB, which is a community maintained movie and TV show database. ===== Infuse Pro is available as a optional subscription, and includes a free trial period that begins once your purchase has been confirmed with your iTunes Account. When the trial period concludes, your subscription will start and renew automatically. Your Apple account will be charged for the upcoming period unless you disable auto-renew or cancel your subscription in your Account Settings at least 24-hours prior to the end of the current period. Visit firecore.com/terms-privacy for full terms and privacy policy. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "55791694977085440",
      "image": "https://is1-ssl.mzstatic.com/image/thumb/Purple211/v4/5a/46/5f/5a465f88-5b62-ac40-ccd7-25f7f63506f9/AppIconMac-0-0-1x_U007euniversal-0-1-0-0-0-0-85-220.png/1200x630wa.png",
      "ownerUserId": null,
      "siteUrl": "https://apps.apple.com/us/app/id1136220934",
      "title": "Infuse - Apple App Store",
      "type": "feed",
      "url": "rsshub://apple/apps/update/us/id1136220934/All"
    }
  ],
  "view": 5
}
```
