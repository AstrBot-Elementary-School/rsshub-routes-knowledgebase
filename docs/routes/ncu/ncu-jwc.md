# 南昌大学 - 教务通知

## Coverage
`index-only`

## Route
- Namespace: `ncu`
- Namespace Name: `南昌大学`
- Route Path: `/ncu/jwc`
- Route Name: `教务通知`
- Example: `/ncu/jwc`
- URL: `jwc.ncu.edu.cn/Notices.jsp`
- Language: `_None_`
- Categories: `university`
- Maintainers: `ywh555hhh, jixiuweilan`
- Source Location: `jwc.ts`
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
  - `jwc.ncu.edu.cn`
- `target`: `/jwc`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/ncu/jwc",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 4,
  "location": "jwc.ts",
  "maintainers": [
    "ywh555hhh",
    "jixiuweilan"
  ],
  "name": "教务通知",
  "parameters": {},
  "path": "/jwc",
  "radar": [
    {
      "source": [
        "jwc.ncu.edu.cn"
      ],
      "target": "/jwc"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "南昌大学教务处通知公告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "84074938770906112",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://jwc.ncu.edu.cn/Notices.jsp?urltype=tree.TreeTempUrl&wbtreeid=1541",
      "title": "南昌大学教务处 - 通知公告",
      "type": "feed",
      "url": "rsshub://ncu/jwc"
    }
  ],
  "url": "jwc.ncu.edu.cn/Notices.jsp"
}
```
