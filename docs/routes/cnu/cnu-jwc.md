# 首都师范大学 - 教务处通知公示

## Coverage
`index-only`

## Route
- Namespace: `cnu`
- Namespace Name: `首都师范大学`
- Route Path: `/cnu/jwc`
- Route Name: `教务处通知公示`
- Example: `/cnu/jwc`
- URL: `jwc.cnu.edu.cn/tzgg/index.htm`
- Language: `_None_`
- Categories: `university`
- Maintainers: `liueic`
- Source Location: `jwc.ts`
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
  - `jwc.cnu.edu.cn/tzgg/index.htm`
- `target`: `/cnu/jwc`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/cnu/jwc",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "jwc.ts",
  "maintainers": [
    "liueic"
  ],
  "name": "教务处通知公示",
  "parameters": {},
  "path": "/jwc",
  "radar": [
    {
      "source": [
        "jwc.cnu.edu.cn/tzgg/index.htm"
      ],
      "target": "/cnu/jwc"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "jwc.cnu.edu.cn/tzgg/index.htm"
}
```
