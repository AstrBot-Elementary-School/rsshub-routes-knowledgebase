# iRead 趣读 - 盐选故事搜索

## Coverage
`index-only`

## Route
- Namespace: `ifun`
- Namespace Name: `iRead 趣读`
- Route Path: `/ifun/n/search/:keywords`
- Route Name: `盐选故事搜索`
- Example: `/ifun/n/search/NPC`
- URL: `iread.life`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `n/search.ts`
- Source Module: `_None_`

## Description
在 [iRead 故事](https://iread.life/articles) 页面输入搜索词。例如关键词 `NPC` 对应 `/ifun/n/search/NPC`。网站搜索条件不保存在 URL 中，请手动填写路由关键词。

## Parameters
- `keywords`: 搜索关键字


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "在 [iRead 故事](https://iread.life/articles) 页面输入搜索词。例如关键词 `NPC` 对应 `/ifun/n/search/NPC`。网站搜索条件不保存在 URL 中，请手动填写路由关键词。",
  "example": "/ifun/n/search/NPC",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "n/search.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "盐选故事搜索",
  "parameters": {
    "keywords": "搜索关键字"
  },
  "path": "/n/search/:keywords",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "iread.life",
  "view": 0
}
```
