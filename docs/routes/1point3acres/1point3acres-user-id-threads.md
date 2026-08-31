# 一亩三分地 - 用户主题帖

## Coverage
`index-only`

## Route
- Namespace: `1point3acres`
- Namespace Name: `一亩三分地`
- Route Path: `/1point3acres/user/:id/threads`
- Route Name: `用户主题帖`
- Example: `/1point3acres/user/1/threads`
- URL: `blog.1point3acres.com`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `Maecenas`
- Source Location: `user/thread.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 用户 id，可在 Instant 版网站的个人主页 URL 找到


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
  - `instant.1point3acres.com/profile/:id`
  - `instant.1point3acres.com/`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/1point3acres/user/1/threads",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "user/thread.ts",
  "maintainers": [
    "Maecenas"
  ],
  "name": "用户主题帖",
  "parameters": {
    "id": "用户 id，可在 Instant 版网站的个人主页 URL 找到"
  },
  "path": "/user/:id/threads",
  "radar": [
    {
      "source": [
        "instant.1point3acres.com/profile/:id",
        "instant.1point3acres.com/"
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
