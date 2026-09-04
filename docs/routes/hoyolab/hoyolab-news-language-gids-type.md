# HoYoLAB - Official Announcement

## Coverage
`index-only`

## Route
- Namespace: `hoyolab`
- Namespace Name: `HoYoLAB`
- Route Path: `/hoyolab/news/:language/:gids/:type`
- Route Name: `Official Announcement`
- Example: `/hoyolab/news/zh-cn/2/2`
- URL: `hoyolab.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `ZenoTian`
- Source Location: `news.tsx`
- Source Module: `_None_`

## Description
| Language         | Code  |
| ---------------- | ----- |
| 简体中文         | zh-cn |
| 繁體中文         | zh-tw |
| 日本語           | ja-jp |
| 한국어           | ko-kr |
| English (US)     | en-us |
| Español (EU)     | es-es |
| Français         | fr-fr |
| Deutsch          | de-de |
| Русский          | ru-ru |
| Português        | pt-pt |
| Español (Latino) | es-mx |
| Indonesia        | id-id |
| Tiếng Việt       | vi-vn |
| ภาษาไทย          | th-th |

| Honkai Impact 3rd | Genshin Impact | Tears of Themis | HoYoLAB | Honkai: Star Rail | Zenless Zone Zero |
| ----------------- | -------------- | --------------- | ------- | ----------------- | ----------------- |
| 1                 | 2              | 4               | 5       | 6                 | 8                 |

| Notices | Events | Info |
| ------- | ------ | ---- |
| 1       | 2      | 3    |

## Parameters
- `language`: Language
- `gids`: Game ID
- `type`: Announcement type


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "| Language         | Code  |\n| ---------------- | ----- |\n| 简体中文         | zh-cn |\n| 繁體中文         | zh-tw |\n| 日本語           | ja-jp |\n| 한국어           | ko-kr |\n| English (US)     | en-us |\n| Español (EU)     | es-es |\n| Français         | fr-fr |\n| Deutsch          | de-de |\n| Русский          | ru-ru |\n| Português        | pt-pt |\n| Español (Latino) | es-mx |\n| Indonesia        | id-id |\n| Tiếng Việt       | vi-vn |\n| ภาษาไทย          | th-th |\n\n| Honkai Impact 3rd | Genshin Impact | Tears of Themis | HoYoLAB | Honkai: Star Rail | Zenless Zone Zero |\n| ----------------- | -------------- | --------------- | ------- | ----------------- | ----------------- |\n| 1                 | 2              | 4               | 5       | 6                 | 8                 |\n\n| Notices | Events | Info |\n| ------- | ------ | ---- |\n| 1       | 2      | 3    |",
  "example": "/hoyolab/news/zh-cn/2/2",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 75,
  "location": "news.tsx",
  "maintainers": [
    "ZenoTian"
  ],
  "name": "Official Announcement",
  "parameters": {
    "gids": "Game ID",
    "language": "Language",
    "type": "Announcement type"
  },
  "path": "/news/:language/:gids/:type",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "HoYoLAB-绝区零-公告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "74614328202293248",
      "image": "https://hyl-static-res-prod.hoyolab.com/communityweb/business/nap.png",
      "ownerUserId": null,
      "siteUrl": "https://www.hoyolab.com/circles/8/47/official?page_type=47&page_sort=notices",
      "title": "HoYoLAB-绝区零-公告",
      "type": "feed",
      "url": "rsshub://hoyolab/news/zh-cn/8/1"
    },
    {
      "description": "HoYoLAB-绝区零-资讯 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "74613800923448320",
      "image": "https://hyl-static-res-prod.hoyolab.com/communityweb/business/nap.png",
      "ownerUserId": null,
      "siteUrl": "https://www.hoyolab.com/circles/8/47/official?page_type=47&page_sort=news",
      "title": "HoYoLAB-绝区零-资讯",
      "type": "feed",
      "url": "rsshub://hoyolab/news/zh-cn/8/3"
    }
  ]
}
```
