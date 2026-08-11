# BT影视 - BTBTLA | 指定剧名

## Coverage
`index-only`

## Route
- Namespace: `btbtla`
- Namespace Name: `BT影视`
- Route Path: `/btbtla/detail/:name`
- Route Name: `BTBTLA | 指定剧名`
- Example: `/btbtla/detail/雍正王朝`
- URL: `www.btbtla.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `Hermes1030`
- Source Location: `detail.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `name`: 电影 | 电视剧名称


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: true
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
  "example": "/btbtla/detail/雍正王朝",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": true,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "detail.ts",
  "maintainers": [
    "Hermes1030"
  ],
  "name": "BTBTLA | 指定剧名",
  "parameters": {
    "name": "电影 | 电视剧名称"
  },
  "path": "/detail/:name",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
