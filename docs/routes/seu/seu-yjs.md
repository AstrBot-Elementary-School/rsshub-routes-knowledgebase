# 东南大学 - 研究生院全部公告

## Coverage
`index-only`

## Route
- Namespace: `seu`
- Namespace Name: `东南大学`
- Route Path: `/seu/yjs`
- Route Name: `研究生院全部公告`
- Example: `/seu/yjs`
- URL: `seugs.seu.edu.cn/26671/list.htm`
- Language: `_None_`
- Categories: `university`
- Maintainers: `Denkiyohou`
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
  - `seugs.seu.edu.cn/26671/list.htm`
  - `seugs.seu.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/seu/yjs",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "yjs.ts",
  "maintainers": [
    "Denkiyohou"
  ],
  "name": "研究生院全部公告",
  "parameters": {},
  "path": "/yjs",
  "radar": [
    {
      "source": [
        "seugs.seu.edu.cn/26671/list.htm",
        "seugs.seu.edu.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "东南大学研究生公告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "153459055825771520",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://seugs.seu.edu.cn/26671/list.htm",
      "title": "东南大学研究生公告",
      "type": "feed",
      "url": "rsshub://seu/yjs"
    }
  ],
  "url": "seugs.seu.edu.cn/26671/list.htm"
}
```
