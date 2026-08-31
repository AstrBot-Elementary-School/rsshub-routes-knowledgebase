# CUPL - 教务处通知公告

## Coverage
`index-only`

## Route
- Namespace: `cupl`
- Namespace Name: `CUPL`
- Route Path: `/cupl/jwc`
- Route Name: `教务处通知公告`
- Example: `/cupl/jwc`
- URL: `jwc.cupl.edu.cn/index/tzgg.htm`
- Language: `_None_`
- Categories: `university`
- Maintainers: `Fgju`
- Source Location: `jwc.ts`
- Source Module: `_None_`

## Description
中国政法大学教务处通知公告

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
  - `jwc.cupl.edu.cn/index/tzgg.htm`
  - `jwc.cupl.edu.cn/`
- `target`: `/jwc`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "中国政法大学教务处通知公告",
  "example": "/cupl/jwc",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "jwc.ts",
  "maintainers": [
    "Fgju"
  ],
  "name": "教务处通知公告",
  "path": "/jwc",
  "radar": [
    {
      "source": [
        "jwc.cupl.edu.cn/index/tzgg.htm",
        "jwc.cupl.edu.cn/"
      ],
      "target": "/jwc"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "中国政法大学教务处通知公告 - Powered by RSSHub",
      "errorAt": "2025-09-08T09:26:47.844Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "129969361217986560",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://jwc.cupl.edu.cn/index/tzgg.htm",
      "title": "通知公告",
      "type": "feed",
      "url": "rsshub://cupl/jwc"
    }
  ],
  "url": "jwc.cupl.edu.cn/index/tzgg.htm"
}
```
