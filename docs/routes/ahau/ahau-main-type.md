# 安徽农业大学 - 安农大官网新闻

## Coverage
`index-only`

## Route
- Namespace: `ahau`
- Namespace Name: `安徽农业大学`
- Route Path: `/ahau/main/:type`
- Route Name: `安农大官网新闻`
- Example: `/ahau/main/xnyw`
- URL: `ahau.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `SimonHu-HN`
- Source Location: `main.ts`
- Source Module: `_None_`

## Description
| 校内要闻 | 院部动态 |
| -------- | -------- |
| xnyw     | ybdt     |

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
  "description": "| 校内要闻 | 院部动态 |\n| -------- | -------- |\n| xnyw     | ybdt     |",
  "example": "/ahau/main/xnyw",
  "heat": 0,
  "location": "main.ts",
  "maintainers": [
    "SimonHu-HN"
  ],
  "name": "安农大官网新闻",
  "parameters": {
    "type": "类型名"
  },
  "path": "/main/:type",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
