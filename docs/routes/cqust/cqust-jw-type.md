# 重庆科技学院 - 教务处公告

## Coverage
`index-only`

## Route
- Namespace: `cqust`
- Namespace Name: `重庆科技学院`
- Route Path: `/cqust/jw/:type?`
- Route Name: `教务处公告`
- Example: `/cqust/jw/notify`
- URL: `www.cqust.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `binarization`
- Source Location: `jw.ts`
- Source Module: `_None_`

## Description
| 通知公告 | 教务快讯 |
| -------- | -------- |
| notify   | news     |

## Parameters
- `type`: 可选，默认为 `notify`


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
  "description": "| 通知公告 | 教务快讯 |\n| -------- | -------- |\n| notify   | news     |",
  "example": "/cqust/jw/notify",
  "heat": 0,
  "location": "jw.ts",
  "maintainers": [
    "binarization"
  ],
  "name": "教务处公告",
  "parameters": {
    "type": "可选，默认为 `notify`"
  },
  "path": "/jw/:type?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
