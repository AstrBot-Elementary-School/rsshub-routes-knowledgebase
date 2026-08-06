# ePrice - 最新消息

## Coverage
`index-only`

## Route
- Namespace: `eprice`
- Namespace Name: `ePrice`
- Route Path: `/eprice/:region?`
- Route Name: `最新消息`
- Example: `/eprice/tw`
- URL: `eprice.com.tw`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `rss.tsx`
- Source Module: `_None_`

## Description
地区：

| hk   | tw   |
| ---- | ---- |
| 香港 | 台湾 |

## Parameters
- `region`: 地区，预设为 tw


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
    "new-media"
  ],
  "description": "地区：\n\n| hk   | tw   |\n| ---- | ---- |\n| 香港 | 台湾 |",
  "example": "/eprice/tw",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 20,
  "location": "rss.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "name": "最新消息",
  "parameters": {
    "region": "地区，预设为 tw"
  },
  "path": "/:region?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "ePrice.HK 提供您最新的手機新聞，包括最新上市的手機、最詳細的手機評測、或是手機促銷，讓您輕鬆掌握手機的最新資訊。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "64107781491090432",
      "image": "https://img.eprice.com.hk/img/hk/common/header/logo.filpboard.png",
      "ownerUserId": null,
      "siteUrl": "https://www.eprice.com.hk/",
      "title": "手機消息",
      "type": "feed",
      "url": "rsshub://eprice/hk"
    },
    {
      "description": "ePrice 比價王 提供您最新的手機、相機、平板與筆電新聞，包括最新上市的手機、相機、平板與筆電詳細産品評測或是促銷資訊，讓您輕鬆掌握手機、相機、筆電與平板的最新資訊。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "55863624174764032",
      "image": "https://img.eprice.com.tw/img/tw/common/header/logo.filpboard.png",
      "ownerUserId": null,
      "siteUrl": "https://www.eprice.com.tw/",
      "title": "ePrice 比價王 綜合新聞",
      "type": "feed",
      "url": "rsshub://eprice/tw"
    }
  ]
}
```
