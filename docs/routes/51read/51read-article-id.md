# 51Read - 章节

## Coverage
`index-only`

## Route
- Namespace: `51read`
- Namespace Name: `51Read`
- Route Path: `/51read/article/:id`
- Route Name: `章节`
- Example: `/51read/article/152685`
- URL: `m.51read.org`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `lazwa34`
- Source Location: `article.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 小说 id, 可在对应小说页 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `m.51read.org/xiaoshuo/:id`
- `target`: `/article/:id`
### Rule 2
- `source`:
  - `51read.org/xiaoshuo/:id`
- `target`: `/article/:id`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/51read/article/152685",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 11,
  "location": "article.ts",
  "maintainers": [
    "lazwa34"
  ],
  "name": "章节",
  "parameters": {
    "id": "小说 id, 可在对应小说页 URL 中找到"
  },
  "path": "/article/:id",
  "radar": [
    {
      "source": [
        "m.51read.org/xiaoshuo/:id"
      ],
      "target": "/article/:id"
    },
    {
      "source": [
        "51read.org/xiaoshuo/:id"
      ],
      "target": "/article/:id"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "杂谈小说《鹅绒锁》_完整目录在线全文阅读 - Powered by RSSHub",
      "errorAt": "2026-06-23T13:58:20.047Z",
      "errorMessage": "[GET] \"https://m.51read.org/zhangjiemulu/152685\": 403 Forbidden\n",
      "id": "60329035500625920",
      "image": "https://cdn.tongjiba.top/public/image/nocover.jpg",
      "ownerUserId": null,
      "siteUrl": "https://m.51read.org/xiaoshuo/152685",
      "title": "鹅绒锁",
      "type": "feed",
      "url": "rsshub://51read/article/152685"
    },
    {
      "description": "宁尘暑假旅游，误入两千年开启一次的传送阵，意外穿越到修真界。修成元婴期后归来，本以为地球早已沧海桑田，没想到才过去一个暑假……于是，青州大学的这届新生里，迎来了一位元婴老怪。“你们对元婴期修士的力量一无所知。” - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "68841428950862848",
      "image": "https://51read.org/public/image/nocover.jpg",
      "ownerUserId": null,
      "siteUrl": "https://m.51read.org/xiaoshuo/366870",
      "title": "我都元婴期了你跟我说开学宁尘许舒颜",
      "type": "feed",
      "url": "rsshub://51read/article/366870"
    }
  ],
  "url": "m.51read.org"
}
```
