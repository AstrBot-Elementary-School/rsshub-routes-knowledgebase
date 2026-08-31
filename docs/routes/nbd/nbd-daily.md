# 每经网 - 重磅原创

## Coverage
`index-only`

## Route
- Namespace: `nbd`
- Namespace Name: `每经网`
- Route Path: `/nbd/daily`
- Route Name: `重磅原创`
- Example: `/nbd/daily`
- URL: `nbd.com.cn/`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `yuuow`
- Source Location: `daily.ts`
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
  - `nbd.com.cn/`
  - `nbd.com.cn/columns/332`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/nbd/daily",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "daily.ts",
  "maintainers": [
    "yuuow"
  ],
  "name": "重磅原创",
  "parameters": {},
  "path": "/daily",
  "radar": [
    {
      "source": [
        "nbd.com.cn/",
        "nbd.com.cn/columns/332"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 301 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "nbd.com.cn/"
}
```
