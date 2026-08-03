# 南开大学 - 教务处通知公告

## Coverage
`index-only`

## Route
- Namespace: `nankai`
- Namespace Name: `南开大学`
- Route Path: `/nankai/jwc`
- Route Name: `教务处通知公告`
- Example: `/nankai/jwc`
- URL: `jwc.nankai.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `vicguo0724`
- Source Location: `jwc.ts`
- Source Module: `_None_`

## Description
南开大学教务处通知公告

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
  - `jwc.nankai.edu.cn/tzgg/list.htm`
- `target`: `/jwc`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "南开大学教务处通知公告",
  "example": "/nankai/jwc",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "jwc.ts",
  "maintainers": [
    "vicguo0724"
  ],
  "name": "教务处通知公告",
  "parameters": {},
  "path": "/jwc",
  "radar": [
    {
      "source": [
        "jwc.nankai.edu.cn/tzgg/list.htm"
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
      "description": "南开大学教务处-通知公告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "168827777043185664",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://jwc.nankai.edu.cn/tzgg/list.htm",
      "title": "南开大学教务处-通知公告",
      "type": "feed",
      "url": "rsshub://nankai/jwc"
    }
  ],
  "url": "jwc.nankai.edu.cn"
}
```
