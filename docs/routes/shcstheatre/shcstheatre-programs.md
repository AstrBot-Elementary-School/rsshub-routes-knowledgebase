# 上海文化广场 - 节目列表

## Coverage
`index-only`

## Route
- Namespace: `shcstheatre`
- Namespace Name: `上海文化广场`
- Route Path: `/shcstheatre/programs`
- Route Name: `节目列表`
- Example: `/shcstheatre/programs`
- URL: `www.shcstheatre.com/Program/programList.aspx`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `fuzy112`
- Source Location: `programs.tsx`
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
  - `www.shcstheatre.com/Program/programList.aspx`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "example": "/shcstheatre/programs",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 218,
  "location": "programs.tsx",
  "maintainers": [
    "fuzy112"
  ],
  "name": "节目列表",
  "parameters": {},
  "path": "/programs",
  "radar": [
    {
      "source": [
        "www.shcstheatre.com/Program/programList.aspx"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "上海文化广场 - 节目列表 - Powered by RSSHub",
      "errorAt": "2026-08-30T04:37:44.106Z",
      "errorMessage": "Cannot read properties of undefined (reading 'tblprogram')\n",
      "id": "57678974871415814",
      "image": "https://static-pc.shcstheatre.com/images/logo1.png",
      "ownerUserId": null,
      "siteUrl": "https://www.shcstheatre.com/Program/programList.aspx",
      "title": "上海文化广场 - 节目列表",
      "type": "feed",
      "url": "rsshub://shcstheatre/programs"
    }
  ],
  "url": "www.shcstheatre.com/Program/programList.aspx"
}
```
