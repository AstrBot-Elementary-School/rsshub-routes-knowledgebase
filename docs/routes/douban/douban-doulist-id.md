# 豆瓣 - 豆瓣豆列

## Coverage
`index-only`

## Route
- Namespace: `douban`
- Namespace Name: `豆瓣`
- Route Path: `/douban/doulist/:id`
- Route Name: `豆瓣豆列`
- Example: `/douban/doulist/37716774`
- URL: `www.douban.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `LogicJake, honue`
- Source Location: `other/doulist.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 豆列id


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
  "example": "/douban/doulist/37716774",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 9,
  "location": "other/doulist.ts",
  "maintainers": [
    "LogicJake",
    "honue"
  ],
  "name": "豆瓣豆列",
  "parameters": {
    "id": "豆列id"
  },
  "path": "/doulist/:id",
  "test": {
    "code": 1,
    "message": "AssertionError: expected NaN to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:61:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "生活常识 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "218331825094149120",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.douban.com/doulist/153767244",
      "title": "生活常识",
      "type": "feed",
      "url": "rsshub://douban/doulist/153767244"
    },
    {
      "description": "通向牛逼之路。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "74703252055644160",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.douban.com/doulist/37716774",
      "title": "记住这些我觉得你就应该很牛掰了",
      "type": "feed",
      "url": "rsshub://douban/doulist/37716774"
    }
  ]
}
```
