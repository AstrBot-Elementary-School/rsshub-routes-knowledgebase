# 米哈游 - 米游社 - 用户帖子

## Coverage
`index-only`

## Route
- Namespace: `mihoyo`
- Namespace Name: `米哈游`
- Route Path: `/mihoyo/bbs/user-post/:uid`
- Route Name: `米游社 - 用户帖子`
- Example: `/mihoyo/bbs/user-post/77005350`
- URL: `genshin.hoyoverse.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `CaoMeiYouRen`
- Source Location: `bbs/user-post.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `uid`: 用户uid


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
    "game"
  ],
  "example": "/mihoyo/bbs/user-post/77005350",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 21,
  "location": "bbs/user-post.ts",
  "maintainers": [
    "CaoMeiYouRen"
  ],
  "name": "米游社 - 用户帖子",
  "parameters": {
    "uid": "用户uid"
  },
  "path": "/bbs/user-post/:uid",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at runNextTicks (node:internal/process/task_queues:69:3)\n    at processImmediate (node:internal/timers:472:9)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "米游社 - HoYo青枫 的发帖 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "198686370602166272",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.miyoushe.com/ys/accountCenter/postList?id=285802042",
      "title": "米游社 - HoYo青枫 的发帖",
      "type": "feed",
      "url": "rsshub://mihoyo/bbs/user-post/285802042"
    },
    {
      "description": "米游社 - 初始镜像OriginMirror 的发帖 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "198686272342260736",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.miyoushe.com/ys/accountCenter/postList?id=159117584",
      "title": "米游社 - 初始镜像OriginMirror 的发帖",
      "type": "feed",
      "url": "rsshub://mihoyo/bbs/user-post/159117584"
    }
  ]
}
```
