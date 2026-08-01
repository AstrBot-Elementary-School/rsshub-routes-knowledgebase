# 中国科普博览 - 直播回看

## Coverage
`index-only`

## Route
- Namespace: `kepu`
- Namespace Name: `中国科普博览`
- Route Path: `/kepu/live`
- Route Name: `直播回看`
- Example: `/kepu/live`
- URL: `live.kepu.net.cn/replay/index`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `live.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: true
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `live.kepu.net.cn/replay/index`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/kepu/live",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": true,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 5,
  "location": "live.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "直播回看",
  "parameters": {},
  "path": "/live",
  "radar": [
    {
      "source": [
        "live.kepu.net.cn/replay/index"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "科学直播(live.kepu.net.cn) - Powered by RSSHub",
      "errorAt": "2026-05-17T15:37:50.433Z",
      "errorMessage": "[POST] \"https://live.kepu.net.cn:8089/index.php/front/live/replay_url\": 500 Internal Server Error\n",
      "id": "63118600077338630",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://live.kepu.net.cn/replay/index",
      "title": "中国科普博览 - 直播回看",
      "type": "feed",
      "url": "rsshub://kepu/live"
    }
  ],
  "url": "live.kepu.net.cn/replay/index"
}
```
