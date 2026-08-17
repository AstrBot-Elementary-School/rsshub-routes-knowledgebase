# 青岛大学 - 教务处通知

## Coverage
`index-only`

## Route
- Namespace: `qdu`
- Namespace Name: `青岛大学`
- Route Path: `/qdu/jwc`
- Route Name: `教务处通知`
- Example: `/qdu/jwc`
- URL: `jwc.qdu.edu.cn/jwtz.htm`
- Language: `_None_`
- Categories: `university`
- Maintainers: `abc1763613206`
- Source Location: `jwc.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


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
  - `jwc.qdu.edu.cn/jwtz.htm`
  - `jwc.qdu.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/qdu/jwc",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "jwc.ts",
  "maintainers": [
    "abc1763613206"
  ],
  "name": "教务处通知",
  "parameters": {},
  "path": "/jwc",
  "radar": [
    {
      "source": [
        "jwc.qdu.edu.cn/jwtz.htm",
        "jwc.qdu.edu.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "jwc.qdu.edu.cn/jwtz.htm"
}
```
