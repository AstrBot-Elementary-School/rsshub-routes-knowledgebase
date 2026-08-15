# 豆瓣 - 豆瓣电影人

## Coverage
`index-only`

## Route
- Namespace: `douban`
- Namespace Name: `豆瓣`
- Route Path: `/douban/celebrity/:id/:sort?`
- Route Name: `豆瓣电影人`
- Example: `/douban/celebrity/1274261`
- URL: `www.douban.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `minimalistrojan`
- Source Location: `other/celebrity.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 电影人 id
- `sort`: 排序方式，缺省为 `time`（时间排序），可为 `vote` （评价排序）


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
  "example": "/douban/celebrity/1274261",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 5,
  "location": "other/celebrity.ts",
  "maintainers": [
    "minimalistrojan"
  ],
  "name": "豆瓣电影人",
  "parameters": {
    "id": "电影人 id",
    "sort": "排序方式，缺省为 `time`（时间排序），可为 `vote` （评价排序）"
  },
  "path": "/celebrity/:id/:sort?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "豆瓣电影人 - 贾樟柯 Zhangke Jia - Powered by RSSHub",
      "errorAt": "2026-03-07T18:33:37.510Z",
      "errorMessage": "[GET] \"https://movie.douban.com/celebrity/1274261/movies?sortby=time\": 403 Forbidden\n",
      "id": "70731857289574400",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://movie.douban.com/celebrity/1274261/movies?sortby=time",
      "title": "豆瓣电影人 - 贾樟柯 Zhangke Jia",
      "type": "feed",
      "url": "rsshub://douban/celebrity/1274261"
    },
    {
      "description": "豆瓣电影人 - 小林聪美 Satomi Kobayashi - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "195039420078972928",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://movie.douban.com/celebrity/1019714/movies?sortby=time",
      "title": "豆瓣电影人 - 小林聪美 Satomi Kobayashi",
      "type": "feed",
      "url": "rsshub://douban/celebrity/1019714"
    }
  ]
}
```
