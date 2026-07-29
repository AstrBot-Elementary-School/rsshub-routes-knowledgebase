# 中国海洋大学 - 信息科学与工程学院

## Coverage
`index-only`

## Route
- Namespace: `ouc`
- Namespace Name: `中国海洋大学`
- Route Path: `/ouc/it/:type?`
- Route Name: `信息科学与工程学院`
- Example: `/ouc/it/0`
- URL: `it.ouc.edu.cn/`
- Language: `_None_`
- Categories: `university`
- Maintainers: `GeoffreyChen777, 3401797899`
- Source Location: `it.ts`
- Source Module: `_None_`

## Description
| 学院要闻 | 学院公告 | 学院活动 |
| -------- | -------- | -------- |
| 0        | 1        | 2        |

## Parameters
- `type`: 默认为 `0`


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
  - `it.ouc.edu.cn/`
- `target`: `/it`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 学院要闻 | 学院公告 | 学院活动 |\n| -------- | -------- | -------- |\n| 0        | 1        | 2        |",
  "example": "/ouc/it/0",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "it.ts",
  "maintainers": [
    "GeoffreyChen777",
    "3401797899"
  ],
  "name": "信息科学与工程学院",
  "parameters": {
    "type": "默认为 `0`"
  },
  "path": "/it/:type?",
  "radar": [
    {
      "source": [
        "it.ouc.edu.cn/"
      ],
      "target": "/it"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at runNextTicks (node:internal/process/task_queues:69:3)\n    at listOnTimeout (node:internal/timers:567:9)\n    at processTimers (node:internal/timers:541:7)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "it.ouc.edu.cn/"
}
```
