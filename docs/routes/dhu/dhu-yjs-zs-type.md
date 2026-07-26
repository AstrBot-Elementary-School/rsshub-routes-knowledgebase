# 东华大学 - 研究生招生信息

## Coverage
`index-only`

## Route
- Namespace: `dhu`
- Namespace Name: `东华大学`
- Route Path: `/dhu/yjs/zs/:type?`
- Route Name: `研究生招生信息`
- Example: `/dhu/yjs/zs/master`
- URL: `www.dhu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `fox2049`
- Source Location: `yjs/zs.ts`
- Source Module: `_None_`

## Description
| 博士招生 | 硕士招生 |
| -------- | -------- |
| doctor   | master   |

## Parameters
- `type`: 默认为 `master`


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 博士招生 | 硕士招生 |\n| -------- | -------- |\n| doctor   | master   |",
  "example": "/dhu/yjs/zs/master",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "yjs/zs.ts",
  "maintainers": [
    "fox2049"
  ],
  "name": "研究生招生信息",
  "parameters": {
    "type": "默认为 `master`"
  },
  "path": "/yjs/zs/:type?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at runNextTicks (node:internal/process/task_queues:69:3)\n    at listOnTimeout (node:internal/timers:567:9)\n    at processTimers (node:internal/timers:541:7)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
