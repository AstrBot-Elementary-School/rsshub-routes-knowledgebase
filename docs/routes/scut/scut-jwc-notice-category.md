# 华南理工大学 - 教务处通知公告

## Coverage
`index-only`

## Route
- Namespace: `scut`
- Namespace Name: `华南理工大学`
- Route Path: `/scut/jwc/notice/:category?`
- Route Name: `教务处通知公告`
- Example: `/scut/jwc/notice/all`
- URL: `jw.scut.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `imkero`
- Source Location: `jwc/notice.ts`
- Source Module: `_None_`

## Description
| 全部 | 选课   | 考试 | 实践     | 交流          | 教师    | 信息 |
| ---- | ------ | ---- | -------- | ------------- | ------- | ---- |
| all  | course | exam | practice | communication | teacher | info |

## Parameters
- `category`: 通知分类，默认为 `all`


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
  "description": "| 全部 | 选课   | 考试 | 实践     | 交流          | 教师    | 信息 |\n| ---- | ------ | ---- | -------- | ------------- | ------- | ---- |\n| all  | course | exam | practice | communication | teacher | info |",
  "example": "/scut/jwc/notice/all",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "jwc/notice.ts",
  "maintainers": [
    "imkero"
  ],
  "name": "教务处通知公告",
  "parameters": {
    "category": "通知分类，默认为 `all`"
  },
  "path": "/jwc/notice/:category?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
