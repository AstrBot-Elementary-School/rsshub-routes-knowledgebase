# Hentai Cosplays - 最新图片

## Coverage
`index-only`

## Route
- Namespace: `hentai-cosplays-xxx`
- Namespace Name: `Hentai Cosplays`
- Route Path: `/hentai-cosplays-xxx/:type?/:name?`
- Route Name: `最新图片`
- Example: `/hentai-cosplays-xxx/tag/jk`
- URL: `hentai-cosplay-xxx.com`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `hoilc`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: 搜索类型, `tag`为标签, `keyword`为关键字, 默认留空为全部
- `name`: 搜索内容, 可在 URL 中找到，默认留空为全部


## Features
- `antiCrawler`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/hentai-cosplays-xxx/tag/jk",
  "features": {
    "antiCrawler": true
  },
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "hoilc"
  ],
  "name": "最新图片",
  "parameters": {
    "name": "搜索内容, 可在 URL 中找到，默认留空为全部",
    "type": "搜索类型, `tag`为标签, `keyword`为关键字, 默认留空为全部"
  },
  "path": "/:type?/:name?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
