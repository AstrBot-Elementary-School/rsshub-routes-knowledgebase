# 豆瓣 - 豆瓣书店

## Coverage
`index-only`

## Route
- Namespace: `douban`
- Namespace Name: `豆瓣`
- Route Path: `/douban/bookstore`
- Route Name: `豆瓣书店`
- Example: `/douban/bookstore`
- URL: `www.douban.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `xyqfer`
- Source Location: `other/bookstore.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


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
  "example": "/douban/bookstore",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 24,
  "location": "other/bookstore.ts",
  "maintainers": [
    "xyqfer"
  ],
  "name": "豆瓣书店",
  "parameters": {},
  "path": "/bookstore",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "在豆瓣书店，遇见美好·書生活 - Powered by RSSHub",
      "errorAt": "2026-04-22T02:02:53.102Z",
      "errorMessage": "[GET] \"https://market.douban.com/api/freyr/books?page=1&page_size=20&type=book\": 404 Not Found\n",
      "id": "41701277991209984",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://market.douban.com/book/",
      "title": "豆瓣书店",
      "type": "feed",
      "url": "rsshub://douban/bookstore"
    }
  ]
}
```
