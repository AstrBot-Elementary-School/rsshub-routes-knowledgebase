# 東立出版社 - 新聞

## Coverage
`index-only`

## Route
- Namespace: `tongli`
- Namespace Name: `東立出版社`
- Route Path: `/tongli/news/:type`
- Route Name: `新聞`
- Example: `/tongli/news/6`
- URL: `tongli.com.tw`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `CokeMine`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: 分類，可以在“新聞”鏈接中找到


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
    "reading"
  ],
  "example": "/tongli/news/6",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 9,
  "location": "news.ts",
  "maintainers": [
    "CokeMine"
  ],
  "name": "新聞",
  "parameters": {
    "type": "分類，可以在“新聞”鏈接中找到"
  },
  "path": "/news/:type",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "T-NEWS首頁 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "78620198692811776",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://docs.rsshub.app/",
      "title": "T-NEWS首頁",
      "type": "feed",
      "url": "rsshub://tongli/news/6"
    }
  ]
}
```
