# 蜻蜓 FM - 专辑

## Coverage
`index-only`

## Route
- Namespace: `qingting`
- Namespace Name: `蜻蜓 FM`
- Route Path: `/qingting/channel/:id`
- Route Name: `专辑`
- Example: `/qingting/channel/293411`
- URL: `qingting.fm`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `nczitzk, pseudoyu`
- Source Location: `channel.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 专辑id, 可在专辑页 URL 中找到


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
    "multimedia"
  ],
  "example": "/qingting/channel/293411",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 25,
  "location": "channel.ts",
  "maintainers": [
    "nczitzk",
    "pseudoyu"
  ],
  "name": "专辑",
  "parameters": {
    "id": "专辑id, 可在专辑页 URL 中找到"
  },
  "path": "/channel/:id",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "圈里圈外InsightOut - 蜻蜓FM - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "165036450856090624",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.qingting.fm/channels/509883",
      "title": "圈里圈外InsightOut - 蜻蜓FM",
      "type": "feed",
      "url": "rsshub://qingting/channel/509883"
    },
    {
      "description": "观棋有语 - 蜻蜓FM - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "43626738504963072",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.qingting.fm/channels/387255",
      "title": "观棋有语 - 蜻蜓FM",
      "type": "feed",
      "url": "rsshub://qingting/channel/387255"
    }
  ]
}
```
