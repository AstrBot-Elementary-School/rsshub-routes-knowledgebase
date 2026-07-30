# 中国技术经济学会 - 栏目

## Coverage
`index-only`

## Route
- Namespace: `cste`
- Namespace Name: `中国技术经济学会`
- Route Path: `/cste/:id?`
- Route Name: `栏目`
- Example: `/cste`
- URL: `cste.org.cn`
- Language: `_None_`
- Categories: `study`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 通知公告 | 学会新闻 | 科协简讯 | 学科动态 | 往事钩沉 |
| -------- | -------- | -------- | -------- | -------- |
| 16       | 18       | 19       | 20       | 21       |

## Parameters
- `id`: 分类，见下表，默认为 16，即通知公告


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
    "study"
  ],
  "description": "| 通知公告 | 学会新闻 | 科协简讯 | 学科动态 | 往事钩沉 |\n| -------- | -------- | -------- | -------- | -------- |\n| 16       | 18       | 19       | 20       | 21       |",
  "example": "/cste",
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
  "name": "栏目",
  "parameters": {
    "id": "分类，见下表，默认为 16，即通知公告"
  },
  "path": "/:id?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
