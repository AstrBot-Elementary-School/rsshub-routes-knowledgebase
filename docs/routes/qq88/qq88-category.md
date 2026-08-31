# 秋爸日字 - 分类

## Coverage
`index-only`

## Route
- Namespace: `qq88`
- Namespace Name: `秋爸日字`
- Route Path: `/qq88/:category?`
- Route Name: `分类`
- Example: `/qq88`
- URL: `qq88.info`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 首页 | オトナの土ドラ | 日剧 | 日剧 SP |
| ---- | -------------- | ---- | ------- |
|      | 10             | 5    | 11      |

## Parameters
- `category`: 分类 id，见下表，默认为首页


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
    "multimedia"
  ],
  "description": "| 首页 | オトナの土ドラ | 日剧 | 日剧 SP |\n| ---- | -------------- | ---- | ------- |\n|      | 10             | 5    | 11      |",
  "example": "/qq88",
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
    "nczitzk"
  ],
  "name": "分类",
  "parameters": {
    "category": "分类 id，见下表，默认为首页"
  },
  "path": "/:category?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
