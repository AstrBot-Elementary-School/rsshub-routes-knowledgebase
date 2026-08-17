# 中国传媒大学 - 研究生招生网

## Coverage
`index-only`

## Route
- Namespace: `cuc`
- Namespace Name: `中国传媒大学`
- Route Path: `/cuc/yz`
- Route Name: `研究生招生网`
- Example: `/cuc/yz`
- URL: `yz.cuc.edu.cn/8549/list.htm`
- Language: `_None_`
- Categories: `university`
- Maintainers: `niuyi1017`
- Source Location: `yz.ts`
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
  - `yz.cuc.edu.cn/8549/list.htm`
  - `yz.cuc.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/cuc/yz",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "yz.ts",
  "maintainers": [
    "niuyi1017"
  ],
  "name": "研究生招生网",
  "parameters": {},
  "path": "/yz",
  "radar": [
    {
      "source": [
        "yz.cuc.edu.cn/8549/list.htm",
        "yz.cuc.edu.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "中国传媒大学研究生招生网 通知公告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "82622855066892288",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://yz.cuc.edu.cn/8549/list.htm",
      "title": "通知公告",
      "type": "feed",
      "url": "rsshub://cuc/yz"
    }
  ],
  "url": "yz.cuc.edu.cn/8549/list.htm"
}
```
