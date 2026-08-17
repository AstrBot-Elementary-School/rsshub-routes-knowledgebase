# 米哈游 - 米游社 - 用户关注

## Coverage
`index-only`

## Route
- Namespace: `mihoyo`
- Namespace Name: `米哈游`
- Route Path: `/mihoyo/bbs/follow-list/:uid`
- Route Name: `米游社 - 用户关注`
- Example: `/mihoyo/bbs/follow-list/77005350`
- URL: `genshin.hoyoverse.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `CaoMeiYouRen`
- Source Location: `bbs/follow-list.ts`
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
  "example": "/mihoyo/bbs/follow-list/77005350",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "bbs/follow-list.ts",
  "maintainers": [
    "CaoMeiYouRen"
  ],
  "name": "米游社 - 用户关注",
  "parameters": {
    "uid": "用户uid"
  },
  "path": "/bbs/follow-list/:uid",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at runNextTicks (node:internal/process/task_queues:69:3)\n    at processImmediate (node:internal/timers:502:9)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "米游社 - 崩坏星穹铁道 的关注 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "116772161376578560",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.miyoushe.com/ys/accountCenter/followList?id=288909600",
      "title": "米游社 - 崩坏星穹铁道 的关注",
      "type": "feed",
      "url": "rsshub://mihoyo/bbs/follow-list/288909600"
    }
  ]
}
```
