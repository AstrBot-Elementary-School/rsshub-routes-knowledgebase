# 黑龙江中医药大学 - 研究生院

## Coverage
`index-only`

## Route
- Namespace: `hljucm`
- Namespace Name: `黑龙江中医药大学`
- Route Path: `/hljucm/yjsy/:category?`
- Route Name: `研究生院`
- Example: `/hljucm/yjsy`
- URL: `yjsy.hljucm.net`
- Language: `_None_`
- Categories: `university`
- Maintainers: `nczitzk`
- Source Location: `yjsy.ts`
- Source Module: `_None_`

## Description
| 新闻动态 | 通知公告 |
| -------- | -------- |
| xwdt     | tzgg     |

## Parameters
- `category`: 分类, 见下表，默认为新闻动态


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
  "description": "| 新闻动态 | 通知公告 |\n| -------- | -------- |\n| xwdt     | tzgg     |",
  "example": "/hljucm/yjsy",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "yjsy.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "研究生院",
  "parameters": {
    "category": "分类, 见下表，默认为新闻动态"
  },
  "path": "/yjsy/:category?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
