# 浪 Play 直播 - 直播间开播

## Coverage
`index-only`

## Route
- Namespace: `lang`
- Namespace Name: `浪 Play 直播`
- Route Path: `/lang/live/room/:id`
- Route Name: `直播间开播`
- Example: `/lang/live/room/1352360`
- URL: `lang.live`
- Language: `_None_`
- Categories: `live`
- Maintainers: `MittWillson`
- Source Location: `room.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 直播间 id, 可在主播直播间页 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `lang.live/room/:id`

## Raw JSON
```json
{
  "categories": [
    "live"
  ],
  "example": "/lang/live/room/1352360",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 58,
  "location": "room.tsx",
  "maintainers": [
    "MittWillson"
  ],
  "name": "直播间开播",
  "parameters": {
    "id": "直播间 id, 可在主播直播间页 URL 中找到"
  },
  "path": "/live/room/:id",
  "radar": [
    {
      "source": [
        "lang.live/room/:id"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "总有些惊奇的际遇，比方说当我遇见你。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "154544860488526848",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.lang.live/room/1352360",
      "title": "🌶穩住！小辣椒～🦖 的浪 Play 直播",
      "type": "feed",
      "url": "rsshub://lang/live/room/1352360"
    }
  ]
}
```
