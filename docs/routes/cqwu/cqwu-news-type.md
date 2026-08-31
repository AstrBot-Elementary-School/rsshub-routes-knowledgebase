# 重庆文理学院 - 通知公告

## Coverage
`index-only`

## Route
- Namespace: `cqwu`
- Namespace Name: `重庆文理学院`
- Route Path: `/cqwu/news/:type?`
- Route Name: `通知公告`
- Example: `/cqwu/news/academiceve`
- URL: `www.cqwu.net`
- Language: `_None_`
- Categories: `university`
- Maintainers: `Fatpandac`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 通知公告 | 学术活动公告 |
| -------- | ------------ |
| notify   | academiceve  |

## Parameters
- `type`: 可选，默认为 academiceve


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
  "description": "| 通知公告 | 学术活动公告 |\n| -------- | ------------ |\n| notify   | academiceve  |",
  "example": "/cqwu/news/academiceve",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "Fatpandac"
  ],
  "name": "通知公告",
  "parameters": {
    "type": "可选，默认为 academiceve "
  },
  "path": "/news/:type?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
