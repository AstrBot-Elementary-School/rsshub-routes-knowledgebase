# 临沂大学 - 新闻

## Coverage
`index-only`

## Route
- Namespace: `lyu`
- Namespace Name: `临沂大学`
- Route Path: `/lyu/news/:type`
- Route Name: `新闻`
- Example: `/lyu/news/ldyw`
- URL: `www.lyu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `ueiu`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| 临大要闻 | 信息公告 |
| -------- | -------- |
| ldyw     | xxgg     |

## Parameters
- `type`: 分类名


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
  "description": "| 临大要闻 | 信息公告 |\n| -------- | -------- |\n| ldyw     | xxgg     |",
  "example": "/lyu/news/ldyw",
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "ueiu"
  ],
  "name": "新闻",
  "parameters": {
    "type": "分类名"
  },
  "path": "/news/:type",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
