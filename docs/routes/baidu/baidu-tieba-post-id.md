# 百度 - 帖子动态

## Coverage
`index-only`

## Route
- Namespace: `baidu`
- Namespace Name: `百度`
- Route Path: `/baidu/tieba/post/:id`
- Route Name: `帖子动态`
- Example: `/baidu/tieba/post/686961453`
- URL: `www.baidu.com`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `u3u`
- Source Location: `tieba/post.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 帖子 ID


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
  - `tieba.baidu.com/p/:id`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/baidu/tieba/post/686961453",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 6,
  "location": "tieba/post.tsx",
  "maintainers": [
    "u3u"
  ],
  "name": "帖子动态",
  "parameters": {
    "id": "帖子 ID"
  },
  "path": [
    "/tieba/post/:id",
    "/tieba/post/lz/:id"
  ],
  "radar": [
    {
      "source": [
        "tieba.baidu.com/p/:id"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "回复：注册求踢帖的最新回复 - Powered by RSSHub",
      "errorAt": "2026-06-08T16:51:35.220Z",
      "errorMessage": "[GET] \"https://tieba.baidu.com/p/9270867907?see_lz=0&pn=7000000&ajax=1\": 403 Forbidden\n",
      "id": "115346513587038208",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://tieba.baidu.com/p/9270867907?see_lz=0",
      "title": "回复：注册求踢帖",
      "type": "feed",
      "url": "rsshub://baidu/tieba/post/9270867907"
    },
    {
      "description": "都2052年了，UE还是没法做到啊的最新回复 - Powered by RSSHub",
      "errorAt": "2025-10-24T21:42:44.797Z",
      "errorMessage": "[GET] \"https://tieba.baidu.com/p/9797499443?see_lz=0&pn=7000000&ajax=1\": 403 Forbidden\n",
      "id": "157675353152621568",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://tieba.baidu.com/p/9797499443?see_lz=0",
      "title": "都2052年了，UE还是没法做到啊",
      "type": "feed",
      "url": "rsshub://baidu/tieba/post/9797499443"
    }
  ]
}
```
