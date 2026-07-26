# 东华大学 - 教务处通知

## Coverage
`index-only`

## Route
- Namespace: `dhu`
- Namespace Name: `东华大学`
- Route Path: `/dhu/jiaowu/news/:type?`
- Route Name: `教务处通知`
- Example: `/dhu/jiaowu/news/student`
- URL: `www.dhu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `KiraKiseki`
- Source Location: `jiaowu/news.ts`
- Source Module: `_None_`

## Description
| 学生专栏 | 教师专栏 | 选课专栏（仅选课期间开放） | 辅修专业 |
| -------- | -------- | -------------------------- | -------- |
| student  | teacher  | class                      | fxzy     |

## Parameters
- `type`: 默认为 `student`


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
  "description": "| 学生专栏 | 教师专栏 | 选课专栏（仅选课期间开放） | 辅修专业 |\n| -------- | -------- | -------------------------- | -------- |\n| student  | teacher  | class                      | fxzy     |",
  "example": "/dhu/jiaowu/news/student",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "jiaowu/news.ts",
  "maintainers": [
    "KiraKiseki"
  ],
  "name": "教务处通知",
  "parameters": {
    "type": "默认为 `student`"
  },
  "path": "/jiaowu/news/:type?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
