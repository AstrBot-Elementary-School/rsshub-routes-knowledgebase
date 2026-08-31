# 洛谷 - 用户动态

## Coverage
`index-only`

## Route
- Namespace: `luogu`
- Namespace Name: `洛谷`
- Route Path: `/luogu/user/feed/:uid`
- Route Name: `用户动态`
- Example: `/luogu/user/feed/1`
- URL: `luogu.com.cn`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `solstice23`
- Source Location: `user-feed.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `uid`: 用户 UID


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
  - `luogu.com/user/:uid`
### Rule 2
- `source`:
  - `luogu.com.cn/user/:uid`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/luogu/user/feed/1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "user-feed.ts",
  "maintainers": [
    "solstice23"
  ],
  "name": "用户动态",
  "parameters": {
    "uid": "用户 UID"
  },
  "path": "/user/feed/:uid",
  "radar": [
    {
      "source": [
        "luogu.com/user/:uid"
      ]
    },
    {
      "source": [
        "luogu.com.cn/user/:uid"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
