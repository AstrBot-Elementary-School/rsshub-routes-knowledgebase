# 酷客影视 - 分类

## Coverage
`index-only`

## Route
- Namespace: `secshi`
- Namespace Name: `酷客影视`
- Route Path: `/secshi/:category?`
- Route Name: `分类`
- Example: `/secshi`
- URL: `www.secshi.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `8430177`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 电影 | 电视剧 | 动漫 | 综艺 | 短剧 | 网飞 |
| ---- | ------ | ---- | ---- | ---- | ---- |
| 1    | 2      | 3    | 4    | 5    | 30   |

## Parameters
- `category`: 分类，见下表，默认为 `1`


## Features
- `antiCrawler`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "| 电影 | 电视剧 | 动漫 | 综艺 | 短剧 | 网飞 |\n| ---- | ------ | ---- | ---- | ---- | ---- |\n| 1    | 2      | 3    | 4    | 5    | 30   |",
  "example": "/secshi",
  "features": {
    "antiCrawler": true
  },
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "8430177"
  ],
  "name": "分类",
  "parameters": {
    "category": "分类，见下表，默认为 `1`"
  },
  "path": "/:category?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "www.secshi.com"
}
```
