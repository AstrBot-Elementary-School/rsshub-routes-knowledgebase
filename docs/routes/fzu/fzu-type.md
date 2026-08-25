# 福州大学 - 教务处通知

## Coverage
`index-only`

## Route
- Namespace: `fzu`
- Namespace Name: `福州大学`
- Route Path: `/fzu/:type`
- Route Name: `教务处通知`
- Example: `/fzu/jxtz`
- URL: `jwch.fzu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `Kare-Udon`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| 教学通知 | 专家讲座 |
| -------- | -------- |
| jxtz     | zjjz     |

## Parameters
- `type`: 分类见下表


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
  "description": "| 教学通知 | 专家讲座 |\n| -------- | -------- |\n| jxtz     | zjjz     |",
  "example": "/fzu/jxtz",
  "features": {
    "antiCrawler": true
  },
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "Kare-Udon"
  ],
  "name": "教务处通知",
  "parameters": {
    "type": "分类见下表"
  },
  "path": "/:type",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
