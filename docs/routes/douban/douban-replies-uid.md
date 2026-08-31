# 豆瓣 - 日记最新回应

## Coverage
`index-only`

## Route
- Namespace: `douban`
- Namespace Name: `豆瓣`
- Route Path: `/douban/replies/:uid`
- Route Name: `日记最新回应`
- Example: `/douban/replies/xiaoyaxiaoya`
- URL: `www.douban.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `nczitzk`
- Source Location: `other/replies.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `uid`: 用户id，可在用户日记页 URL 中找到


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
    "social-media"
  ],
  "example": "/douban/replies/xiaoyaxiaoya",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "other/replies.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "日记最新回应",
  "parameters": {
    "uid": "用户id，可在用户日记页 URL 中找到"
  },
  "path": "/replies/:uid",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
