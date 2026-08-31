# 親子王國 - 板块

## Coverage
`index-only`

## Route
- Namespace: `baby-kingdom`
- Namespace Name: `親子王國`
- Route Path: `/baby-kingdom/:id/:order?`
- Route Name: `板块`
- Example: `/baby-kingdom/19/view`
- URL: `www.baby-kingdom.com`
- Language: `_None_`
- Categories: `other`
- Maintainers: `LogicJake`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 发帖时间 | 回复 / 查看 | 查看 | 最后发表 | 热门 |
| -------- | ----------- | ---- | -------- | ---- |
| dateline | reply       | view | lastpost | heat |

## Parameters
- `id`: 板块id，可在 URL 中找到
- `order`: 排序方式


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "| 发帖时间 | 回复 / 查看 | 查看 | 最后发表 | 热门 |\n| -------- | ----------- | ---- | -------- | ---- |\n| dateline | reply       | view | lastpost | heat |",
  "example": "/baby-kingdom/19/view",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "LogicJake"
  ],
  "name": "板块",
  "parameters": {
    "id": "板块id，可在 URL 中找到",
    "order": "排序方式"
  },
  "path": "/:id/:order?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 321498813844 to be less than 311040000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:62:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
