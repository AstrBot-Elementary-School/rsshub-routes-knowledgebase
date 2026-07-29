# 希望之声 - 频道

## Coverage
`index-only`

## Route
- Namespace: `soundofhope`
- Namespace Name: `希望之声`
- Route Path: `/soundofhope/:channel/:id`
- Route Name: `频道`
- Example: `/soundofhope/term/203`
- URL: `soundofhope.org`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `Fatpandac`
- Source Location: `channel.ts`
- Source Module: `_None_`

## Description
参数均可在官网获取，如：

`https://www.soundofhope.org/term/203` 对应 `/soundofhope/term/203`

## Parameters
- `channel`: 频道
- `id`: 子频道 ID


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
  - `soundofhope.org/:channel/:id`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "参数均可在官网获取，如：\n\n`https://www.soundofhope.org/term/203` 对应 `/soundofhope/term/203`",
  "example": "/soundofhope/term/203",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "channel.ts",
  "maintainers": [
    "Fatpandac"
  ],
  "name": "频道",
  "parameters": {
    "channel": "频道",
    "id": "子频道 ID"
  },
  "path": "/:channel/:id",
  "radar": [
    {
      "source": [
        "soundofhope.org/:channel/:id"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "希望之声 - - Powered by RSSHub",
      "errorAt": "2026-03-15T21:47:18.337Z",
      "errorMessage": "[GET] \"https://www.soundofhope.org/term/1\": 403 Forbidden\n[GET] \"https://www.soundofhope.org/term/1\": 403 Forbidden\n",
      "id": "236706823065107456",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.soundofhope.org/term/1",
      "title": "希望之声 -",
      "type": "feed",
      "url": "rsshub://soundofhope/term/1"
    }
  ]
}
```
