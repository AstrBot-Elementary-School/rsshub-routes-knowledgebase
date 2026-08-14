# 豆瓣 - 话题

## Coverage
`index-only`

## Route
- Namespace: `douban`
- Namespace Name: `豆瓣`
- Route Path: `/douban/topic/:id/:sort?`
- Route Name: `话题`
- Example: `/douban/topic/48823`
- URL: `www.douban.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `LogicJake, pseudoyu, haowenwu`
- Source Location: `other/topic.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 话题id
- `sort`: 排序方式，hot或new，默认为new


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
  "example": "/douban/topic/48823",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 50,
  "location": "other/topic.ts",
  "maintainers": [
    "LogicJake",
    "pseudoyu",
    "haowenwu"
  ],
  "name": "话题",
  "parameters": {
    "id": "话题id",
    "sort": "排序方式，hot或new，默认为new"
  },
  "path": "/topic/:id/:sort?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "48823-豆瓣话题 - Powered by RSSHub",
      "errorAt": "2026-02-27T06:36:35.221Z",
      "errorMessage": "[GET] \"https://m.douban.com/rexxar/api/v2/gallery/topic/48823/items?sort=new&start=0&count=10&status_full_text=1\": 403 Forbidden\n",
      "id": "70440214385169408",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.douban.com/gallery/topic/48823/?sort=new",
      "title": "48823-豆瓣话题",
      "type": "feed",
      "url": "rsshub://douban/topic/48823"
    },
    {
      "description": "收集一切触动过你的评论-豆瓣话题 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "84419327283379200",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.douban.com/gallery/topic/3379063/?sort=new",
      "title": "收集一切触动过你的评论-豆瓣话题",
      "type": "feed",
      "url": "rsshub://douban/topic/3379063"
    }
  ]
}
```
