# 常州大学 - 新闻网

## Coverage
`index-only`

## Route
- Namespace: `cczu`
- Namespace Name: `常州大学`
- Route Path: `/cczu/news/:category?`
- Route Name: `新闻网`
- Example: `/cczu/news/6620`
- URL: `www.cczu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `stdrc`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| 全部 | 常大要闻 | 校园快讯 | 媒体常大 | 时事热点 | 高教动态 | 网上橱窗 | 新媒常大 |
| ---- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| all  | 6620     | 6621     | 6687     | 6628     | 6629     | 6640     | 6645     |

## Parameters
- `category`: 可选，默认为 `all`


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
  "description": "| 全部 | 常大要闻 | 校园快讯 | 媒体常大 | 时事热点 | 高教动态 | 网上橱窗 | 新媒常大 |\n| ---- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |\n| all  | 6620     | 6621     | 6687     | 6628     | 6629     | 6640     | 6645     |",
  "example": "/cczu/news/6620",
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "stdrc"
  ],
  "name": "新闻网",
  "parameters": {
    "category": "可选，默认为 `all`"
  },
  "path": "/news/:category?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
