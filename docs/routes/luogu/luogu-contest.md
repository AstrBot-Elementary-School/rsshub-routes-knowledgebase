# 洛谷 - 比赛列表

## Coverage
`index-only`

## Route
- Namespace: `luogu`
- Namespace Name: `洛谷`
- Route Path: `/luogu/contest`
- Route Name: `比赛列表`
- Example: `/luogu/contest`
- URL: `luogu.com.cn/contest/list`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `prnake`
- Source Location: `contest.ts`
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
### Rule 1
- `source`:
  - `luogu.com.cn/contest/list`
  - `luogu.com.cn/`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/luogu/contest",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 16,
  "location": "contest.ts",
  "maintainers": [
    "prnake"
  ],
  "name": "比赛列表",
  "parameters": {},
  "path": "/contest",
  "radar": [
    {
      "source": [
        "luogu.com.cn/contest/list",
        "luogu.com.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "比赛列表 - 洛谷 - Powered by RSSHub",
      "errorAt": "2026-03-27T04:47:38.288Z",
      "errorMessage": "Cannot read properties of null (reading '1')\n",
      "id": "56948849407992832",
      "image": "https://www.luogu.com.cn/favicon.ico",
      "ownerUserId": null,
      "siteUrl": "https://www.luogu.com.cn/contest/list",
      "title": "比赛列表 - 洛谷",
      "type": "feed",
      "url": "rsshub://luogu/contest"
    }
  ],
  "url": "luogu.com.cn/contest/list"
}
```
