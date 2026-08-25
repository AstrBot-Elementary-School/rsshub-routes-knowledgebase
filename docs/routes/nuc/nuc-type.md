# 中北大学 - 各种新闻通知

## Coverage
`index-only`

## Route
- Namespace: `nuc`
- Namespace Name: `中北大学`
- Route Path: `/nuc/:type`
- Route Name: `各种新闻通知`
- Example: `/nuc/zbxw`
- URL: `www.nuc.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `Dreace`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 中北新闻 | 通知公告 | 学术活动 | 教务通知 |
| -------- | -------- | -------- | -------- |
| zbxw     | tzgg     | xshd     | jwtz     |

## Parameters
- `type`: 分类，见下表


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 中北新闻 | 通知公告 | 学术活动 | 教务通知 |\n| -------- | -------- | -------- | -------- |\n| zbxw     | tzgg     | xshd     | jwtz     |",
  "example": "/nuc/zbxw",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "Dreace"
  ],
  "name": "各种新闻通知",
  "parameters": {
    "type": "分类，见下表"
  },
  "path": "/:type",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at runNextTicks (node:internal/process/task_queues:69:3)\n    at listOnTimeout (node:internal/timers:597:9)\n    at processTimers (node:internal/timers:571:7)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
