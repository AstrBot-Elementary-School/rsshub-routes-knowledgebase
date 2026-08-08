# 虎扑 - 热帖

## Coverage
`index-only`

## Route
- Namespace: `hupu`
- Namespace Name: `虎扑`
- Route Path: `/hupu/all/:id?`
- Route Name: `热帖`
- Example: `/hupu/all/topic-daily`
- URL: `.hupu.com`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `nczitzk`
- Source Location: `all.tsx`
- Source Module: `_None_`

## Description
::: tip
更多热帖版面参见 [论坛](https://bbs.hupu.com)
:::

## Parameters
- `id`: 编号，可在对应热帖版面 URL 中找到，默认为步行街每日话题


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
  - `m.hupu.com/:category`
  - `m.hupu.com/`
- `target`: `/:category`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "description": "::: tip\n更多热帖版面参见 [论坛](https://bbs.hupu.com)\n:::",
  "example": "/hupu/all/topic-daily",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 769,
  "location": "all.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "热帖",
  "parameters": {
    "id": "编号，可在对应热帖版面 URL 中找到，默认为步行街每日话题"
  },
  "path": "/all/:id?",
  "radar": [
    {
      "source": [
        "m.hupu.com/:category",
        "m.hupu.com/"
      ],
      "target": "/:category"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "虎扑社区 - #步行街主干道 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "53366652701156359",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bbs.hupu.com/topic-daily",
      "title": "虎扑社区 - #步行街主干道",
      "type": "feed",
      "url": "rsshub://hupu/all/topic-daily"
    },
    {
      "description": "虎扑社区 - 步行街热帖 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "63404283121618947",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bbs.hupu.com/all-gambia",
      "title": "虎扑社区 - 步行街热帖",
      "type": "feed",
      "url": "rsshub://hupu/all/all-gambia"
    }
  ]
}
```
