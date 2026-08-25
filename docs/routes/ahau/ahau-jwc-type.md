# 安徽农业大学 - 教务处

## Coverage
`index-only`

## Route
- Namespace: `ahau`
- Namespace Name: `安徽农业大学`
- Route Path: `/ahau/jwc/:type`
- Route Name: `教务处`
- Example: `/ahau/jwc/jwyw`
- URL: `ahau.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `SimonHu-HN`
- Source Location: `jwc.ts`
- Source Module: `_None_`

## Description
| 教务要闻 | 通知公告 |
| -------- | -------- |
| jwyw     | tzgg     |

## Parameters
- `type`: 类型名


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
  "description": "| 教务要闻 | 通知公告 |\n| -------- | -------- |\n| jwyw     | tzgg     |",
  "example": "/ahau/jwc/jwyw",
  "heat": 0,
  "location": "jwc.ts",
  "maintainers": [
    "SimonHu-HN"
  ],
  "name": "教务处",
  "parameters": {
    "type": "类型名"
  },
  "path": "/jwc/:type",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
