# 常州大学 - 教务处

## Coverage
`index-only`

## Route
- Namespace: `cczu`
- Namespace Name: `常州大学`
- Route Path: `/cczu/jwc/:category?`
- Route Name: `教务处`
- Example: `/cczu/jwc/1425`
- URL: `www.cczu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `stdrc`
- Source Location: `jwc.ts`
- Source Module: `_None_`

## Description
| 全部 | 通知公告 | 教务新闻 | 各类活动与系列讲座 | 本科教学工程 | 他山之石 | 信息快递 |
| ---- | -------- | -------- | ------------------ | ------------ | -------- | -------- |
| all  | 1425     | 1437     | 1485               | 1487         | 1442     | 1445     |

## Parameters
- `category`: 可选，默认为 `all`


## Features
- `antiCrawler`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 全部 | 通知公告 | 教务新闻 | 各类活动与系列讲座 | 本科教学工程 | 他山之石 | 信息快递 |\n| ---- | -------- | -------- | ------------------ | ------------ | -------- | -------- |\n| all  | 1425     | 1437     | 1485               | 1487         | 1442     | 1445     |",
  "example": "/cczu/jwc/1425",
  "features": {
    "antiCrawler": true
  },
  "heat": 0,
  "location": "jwc.ts",
  "maintainers": [
    "stdrc"
  ],
  "name": "教务处",
  "parameters": {
    "category": "可选，默认为 `all`"
  },
  "path": "/jwc/:category?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at runNextTicks (node:internal/process/task_queues:69:3)\n    at listOnTimeout (node:internal/timers:597:9)\n    at processTimers (node:internal/timers:571:7)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
