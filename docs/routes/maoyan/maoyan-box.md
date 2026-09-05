# 猫眼电影 - 实时票房榜

## Coverage
`index-only`

## Route
- Namespace: `maoyan`
- Namespace Name: `猫眼电影`
- Route Path: `/maoyan/box`
- Route Name: `实时票房榜`
- Example: `/maoyan/box`
- URL: `maoyan.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `JackyST0`
- Source Location: `box.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


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
  - `piaofang.maoyan.com/dashboard`
- `target`: `/box`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/maoyan/box",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 9,
  "location": "box.ts",
  "maintainers": [
    "JackyST0"
  ],
  "name": "实时票房榜",
  "parameters": {},
  "path": "/box",
  "radar": [
    {
      "source": [
        "piaofang.maoyan.com/dashboard"
      ],
      "target": "/box"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "猫眼电影实时票房排行榜 - Powered by RSSHub",
      "errorAt": "2026-08-13T16:07:34.803Z",
      "errorMessage": "[GET] \"https://piaofang.maoyan.com/dashboard-ajax\": 403 Forbidden\n",
      "id": "237791467801829376",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://piaofang.maoyan.com/dashboard",
      "title": "猫眼实时票房榜",
      "type": "feed",
      "url": "rsshub://maoyan/box"
    }
  ]
}
```
