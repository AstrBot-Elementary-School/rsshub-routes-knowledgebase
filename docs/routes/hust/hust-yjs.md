# 华中科技大学 - 研究生院通知公告

## Coverage
`index-only`

## Route
- Namespace: `hust`
- Namespace Name: `华中科技大学`
- Route Path: `/hust/yjs`
- Route Name: `研究生院通知公告`
- Example: `/hust/yjs`
- URL: `gszs.hust.edu.cn/zsxx/ggtz.htm`
- Language: `_None_`
- Categories: `university`
- Maintainers: `shengmaosu`
- Source Location: `yjs.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `gszs.hust.edu.cn/zsxx/ggtz.htm`
  - `gszs.hust.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/hust/yjs",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 6,
  "location": "yjs.ts",
  "maintainers": [
    "shengmaosu"
  ],
  "name": "研究生院通知公告",
  "parameters": {},
  "path": "/yjs",
  "radar": [
    {
      "source": [
        "gszs.hust.edu.cn/zsxx/ggtz.htm",
        "gszs.hust.edu.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "华中科技大学研究生调剂信息 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "73883177475050496",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://gszs.hust.edu.cn/zsxx/ggtz.htm",
      "title": "华中科技大学研究生院",
      "type": "feed",
      "url": "rsshub://hust/yjs"
    }
  ],
  "url": "gszs.hust.edu.cn/zsxx/ggtz.htm"
}
```
