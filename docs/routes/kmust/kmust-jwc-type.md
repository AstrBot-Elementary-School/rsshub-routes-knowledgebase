# 昆明理工大学 - 教务处

## Coverage
`index-only`

## Route
- Namespace: `kmust`
- Namespace Name: `昆明理工大学`
- Route Path: `/kmust/jwc/:type?`
- Route Name: `教务处`
- Example: `/kmust/jwc/notify`
- URL: `www.kmust.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `geekrainy`
- Source Location: `jwc.ts`
- Source Module: `_None_`

## Description
| 教务通知 | 教务新闻 |
| -------- | -------- |
| notify   | news     |

## Parameters
- `type`: 默认为 `notify`


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
  "description": "| 教务通知 | 教务新闻 |\n| -------- | -------- |\n| notify   | news     |",
  "example": "/kmust/jwc/notify",
  "heat": 0,
  "location": "jwc.ts",
  "maintainers": [
    "geekrainy"
  ],
  "name": "教务处",
  "parameters": {
    "type": "默认为 `notify`"
  },
  "path": "/jwc/:type?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at runNextTicks (node:internal/process/task_queues:69:3)\n    at processTimers (node:internal/timers:568:9)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
