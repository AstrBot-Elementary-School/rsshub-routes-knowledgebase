# Hanime1 - 每月新番

## Coverage
`index-only`

## Route
- Namespace: `hanime1`
- Namespace Name: `Hanime1`
- Route Path: `/hanime1/previews/:date?`
- Route Name: `每月新番`
- Example: `/hanime1/previews/202504`
- URL: `hanime1.me`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `kjasn`
- Source Location: `previews.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `date`: {"description": "日期格式为 `YYYYMM`，默认值当月"}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `hanime1.me/previews/:date`
  - `hanime1.me/previews`
- `target`: `/previews/:date`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/hanime1/previews/202504",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 443,
  "location": "previews.ts",
  "maintainers": [
    "kjasn"
  ],
  "name": "每月新番",
  "parameters": {
    "date": {
      "description": "日期格式为 `YYYYMM`，默认值当月"
    }
  },
  "path": "/previews/:date?",
  "radar": [
    {
      "source": [
        "hanime1.me/previews/:date",
        "hanime1.me/previews"
      ],
      "target": "/previews/:date"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Hanime1 202602 新番 - Powered by RSSHub",
      "errorAt": "2026-02-18T16:19:29.168Z",
      "errorMessage": "[GET] \"https://hanime1.me/previews/202607\": 403 Forbidden\n502 \n[GET] \"https://hanime1.me/previews/202607\": 403 Forbidden\n[GET] \"https://hanime1.me/previews/202607\": 403 Forbidden\n",
      "id": "141164425462660096",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://hanime1.me/previews/202602",
      "title": "Hanime1 202602 新番",
      "type": "feed",
      "url": "rsshub://hanime1/previews"
    },
    {
      "description": "Hanime1 202504 新番 - Powered by RSSHub",
      "errorAt": "2026-02-25T23:45:57.858Z",
      "errorMessage": "[GET] \"https://hanime1.me/previews/202504\": 403 Forbidden\n",
      "id": "133901229760109568",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://hanime1.me/previews/202504",
      "title": "Hanime1 202504 新番",
      "type": "feed",
      "url": "rsshub://hanime1/previews/202504"
    }
  ]
}
```
