# 南京大学 - ITSC 信息中心

## Coverage
`index-only`

## Route
- Namespace: `nju`
- Namespace Name: `南京大学`
- Route Path: `/nju/itsc`
- Route Name: `ITSC 信息中心`
- Example: `/nju/itsc`
- URL: `itsc.nju.edu.cn/tzgg/list.htm`
- Language: `_None_`
- Categories: `university`
- Maintainers: `ret-1`
- Source Location: `itsc.ts`
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
  - `itsc.nju.edu.cn/tzgg/list.htm`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/nju/itsc",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 8,
  "location": "itsc.ts",
  "maintainers": [
    "ret-1"
  ],
  "name": "ITSC 信息中心",
  "parameters": {},
  "path": "/itsc",
  "radar": [
    {
      "source": [
        "itsc.nju.edu.cn/tzgg/list.htm"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "ITSC-公告通知 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "62659849228123136",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://itsc.nju.edu.cn/tzgg/list.htm",
      "title": "ITSC-公告通知",
      "type": "feed",
      "url": "rsshub://nju/itsc"
    }
  ],
  "url": "itsc.nju.edu.cn/tzgg/list.htm"
}
```
