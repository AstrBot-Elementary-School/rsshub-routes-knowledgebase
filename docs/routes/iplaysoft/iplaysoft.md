# 异次元软件世界 - 首页

## Coverage
`index-only`

## Route
- Namespace: `iplaysoft`
- Namespace Name: `异次元软件世界`
- Route Path: `/iplaysoft/`
- Route Name: `首页`
- Example: `/iplaysoft`
- URL: `www.iplaysoft.com`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `kimi360, williamgateszhao, cscnk52, LokHsu`
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
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.iplaysoft.com`
- `target`: `/`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/iplaysoft",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "kimi360",
    "williamgateszhao",
    "cscnk52",
    "LokHsu"
  ],
  "name": "首页",
  "parameters": {},
  "path": "/",
  "radar": [
    {
      "source": [
        "www.iplaysoft.com"
      ],
      "target": "/"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "www.iplaysoft.com",
  "view": 0
}
```
