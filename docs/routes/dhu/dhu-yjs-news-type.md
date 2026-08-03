# 东华大学 - 研究生院通知

## Coverage
`index-only`

## Route
- Namespace: `dhu`
- Namespace Name: `东华大学`
- Route Path: `/dhu/yjs/news/:type?`
- Route Name: `研究生院通知`
- Example: `/dhu/yjs/news/class`
- URL: `www.dhu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `fox2049`
- Source Location: `yjs/news.ts`
- Source Module: `_None_`

## Description
| 新闻动态 | 通知公告 | 选课考试 |
| -------- | -------- | -------- |
| trend    | notice   | class    |

## Parameters
- `type`: 默认为 `class`


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 新闻动态 | 通知公告 | 选课考试 |\n| -------- | -------- | -------- |\n| trend    | notice   | class    |",
  "example": "/dhu/yjs/news/class",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "yjs/news.ts",
  "maintainers": [
    "fox2049"
  ],
  "name": "研究生院通知",
  "parameters": {
    "type": "默认为 `class`"
  },
  "path": "/yjs/news/:type?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
