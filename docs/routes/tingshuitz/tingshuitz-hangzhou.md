# 停水通知 - 杭州市

## Coverage
`index-only`

## Route
- Namespace: `tingshuitz`
- Namespace Name: `停水通知`
- Route Path: `/tingshuitz/hangzhou`
- Route Name: `杭州市`
- Example: `/tingshuitz/hangzhou`
- URL: `www.hzwgc.com/public/stop_the_water`
- Language: `_None_`
- Categories: `forecast`
- Maintainers: `znhocn`
- Source Location: `hangzhou.ts`
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
  - `www.hzwgc.com/public/stop_the_water`
  - `www.hzwgc.com/`

## Raw JSON
```json
{
  "categories": [
    "forecast"
  ],
  "example": "/tingshuitz/hangzhou",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "hangzhou.ts",
  "maintainers": [
    "znhocn"
  ],
  "name": "杭州市",
  "parameters": {},
  "path": "/hangzhou",
  "radar": [
    {
      "source": [
        "www.hzwgc.com/public/stop_the_water",
        "www.hzwgc.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "www.hzwgc.com/public/stop_the_water"
}
```
