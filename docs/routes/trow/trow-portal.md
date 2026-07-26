# The Ring of Wonder - 首页更新

## Coverage
`index-only`

## Route
- Namespace: `trow`
- Namespace Name: `The Ring of Wonder`
- Route Path: `/trow/portal`
- Route Name: `首页更新`
- Example: `/trow/portal`
- URL: `trow.cc/`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `shiningdracon`
- Source Location: `portal.ts`
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
  - `trow.cc/`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/trow/portal",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "portal.ts",
  "maintainers": [
    "shiningdracon"
  ],
  "name": "首页更新",
  "parameters": {},
  "path": "/portal",
  "radar": [
    {
      "source": [
        "trow.cc/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "The Ring of Wonder 首页更新 - Powered by RSSHub",
      "errorAt": "2026-07-04T18:27:28.812Z",
      "errorMessage": "[GET] \"https://trow.cc\": 403 Forbidden\n",
      "id": "1149362207675252736",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://trow.cc/",
      "title": "The Ring of Wonder - Portal",
      "type": "feed",
      "url": "rsshub://trow/portal"
    }
  ],
  "url": "trow.cc/"
}
```
