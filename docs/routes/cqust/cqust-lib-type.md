# 重庆科技学院 - 图书馆公告

## Coverage
`index-only`

## Route
- Namespace: `cqust`
- Namespace Name: `重庆科技学院`
- Route Path: `/cqust/lib/:type?`
- Route Name: `图书馆公告`
- Example: `/cqust/lib/news`
- URL: `www.cqust.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `binarization`
- Source Location: `lib.ts`
- Source Module: `_None_`

## Description
| 本馆公告 |
| -------- |
| news     |

## Parameters
- `type`: 可选，默认为 `news`


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
  "description": "| 本馆公告 |\n| -------- |\n| news     |",
  "example": "/cqust/lib/news",
  "heat": 0,
  "location": "lib.ts",
  "maintainers": [
    "binarization"
  ],
  "name": "图书馆公告",
  "parameters": {
    "type": "可选，默认为 `news`"
  },
  "path": "/lib/:type?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
