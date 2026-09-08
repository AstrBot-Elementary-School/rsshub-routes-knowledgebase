# 爱范儿 - 首页

## Coverage
`index-only`

## Route
- Namespace: `ifanr`
- Namespace Name: `爱范儿`
- Route Path: `/ifanr/index`
- Route Name: `首页`
- Example: `/ifanr/index`
- URL: `www.ifanr.com/index`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `donghongfei`
- Source Location: `index.ts`
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
  - `www.ifanr.com/index`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/ifanr/index",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 546,
  "location": "index.ts",
  "maintainers": [
    "donghongfei"
  ],
  "name": "首页",
  "parameters": {},
  "path": "/index",
  "radar": [
    {
      "source": [
        "www.ifanr.com/index"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at runNextTicks (node:internal/process/task_queues:69:3)\n    at processImmediate (node:internal/timers:541:9)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "爱范儿首页 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "95440076991617024",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.ifanr.com/",
      "title": "爱范儿",
      "type": "feed",
      "url": "rsshub://ifanr/index"
    }
  ],
  "url": "www.ifanr.com/index",
  "view": 0
}
```
