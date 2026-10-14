# 北京理工大学 - 教务处通知

## Coverage
`index-only`

## Route
- Namespace: `bit`
- Namespace Name: `北京理工大学`
- Route Path: `/bit/jwc`
- Route Name: `教务处通知`
- Example: `/bit/jwc`
- URL: `jwb.bit.edu.cn/tzgg/index.htm`
- Language: `_None_`
- Categories: `university`
- Maintainers: `sinofp`
- Source Location: `jwc/jwc.ts`
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
  - `jwb.bit.edu.cn/tzgg/index.htm`
  - `jwb.bit.edu.cn/`
### Rule 2
- `source`:
  - `jwc.bit.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/bit/jwc",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "jwc/jwc.ts",
  "maintainers": [
    "sinofp"
  ],
  "name": "教务处通知",
  "parameters": {},
  "path": "/jwc",
  "radar": [
    {
      "source": [
        "jwb.bit.edu.cn/tzgg/index.htm",
        "jwb.bit.edu.cn/"
      ]
    },
    {
      "source": [
        "jwc.bit.edu.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "jwb.bit.edu.cn/tzgg/index.htm"
}
```
