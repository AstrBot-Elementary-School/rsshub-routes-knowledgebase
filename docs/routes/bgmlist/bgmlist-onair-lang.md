# 番组放送 - 开播提醒

## Coverage
`index-only`

## Route
- Namespace: `bgmlist`
- Namespace Name: `番组放送`
- Route Path: `/bgmlist/onair/:lang?`
- Route Name: `开播提醒`
- Example: `/bgmlist/onair/zh-Hans`
- URL: `bgmlist.com`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `x2cf`
- Source Location: `onair.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `lang`: 语言


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
    "anime"
  ],
  "example": "/bgmlist/onair/zh-Hans",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 36,
  "location": "onair.tsx",
  "maintainers": [
    "x2cf"
  ],
  "name": "开播提醒",
  "parameters": {
    "lang": "语言"
  },
  "path": "/onair/:lang?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "番组放送 开播提醒 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "66094089537608707",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bgmlist.com/",
      "title": "番组放送 开播提醒",
      "type": "feed",
      "url": "rsshub://bgmlist/onair/zh-Hans"
    },
    {
      "description": "番组放送 开播提醒 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "156587319648221184",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bgmlist.com/",
      "title": "番组放送 开播提醒",
      "type": "feed",
      "url": "rsshub://bgmlist/onair"
    }
  ]
}
```
