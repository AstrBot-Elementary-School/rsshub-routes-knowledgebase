# 豆瓣 - 北美票房榜

## Coverage
`index-only`

## Route
- Namespace: `douban`
- Namespace Name: `豆瓣`
- Route Path: `/douban/movie/ustop`
- Route Name: `北美票房榜`
- Example: `/douban/movie/ustop`
- URL: `www.douban.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `DIYgod`
- Source Location: `other/ustop.ts`
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
  "example": "/douban/movie/ustop",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 44,
  "location": "other/ustop.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "北美票房榜",
  "parameters": {},
  "path": "/movie/ustop",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "豆瓣电影北美票房榜 - Powered by RSSHub",
      "errorAt": "2024-12-05T07:51:46.128Z",
      "errorMessage": "[GET] \"https://api.douban.com/v2/movie/us_box?apikey=0df993c66c0c636e29ecbb5344252a4a\": 400 Bad Request\n",
      "id": "59787325142564864",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://movie.douban.com/chart",
      "title": "豆瓣电影北美票房榜",
      "type": "feed",
      "url": "rsshub://douban/movie/ustop"
    }
  ]
}
```
