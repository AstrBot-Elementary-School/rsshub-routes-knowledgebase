# 東森新聞 - 即時新聞

## Coverage
`index-only`

## Route
- Namespace: `ebc`
- Namespace Name: `東森新聞`
- Route Path: `/ebc/realtime/:category?`
- Route Name: `即時新聞`
- Example: `/ebc/realtime/politics`
- URL: `ebc.net.tw`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `quiniapiezoelectricity`
- Source Location: `realtime.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: Category from the last segment of the URL of the corresponding site


## Features
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `requireConfig`: false

## Radar
### Rule 1
- `source`:
  - `news.ebc.net.tw/realtime/:category`
- `target`: `/:category`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "",
  "example": "/ebc/realtime/politics",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 75,
  "location": "realtime.ts",
  "maintainers": [
    "quiniapiezoelectricity"
  ],
  "name": "即時新聞",
  "parameters": {
    "category": "Category from the last segment of the URL of the corresponding site"
  },
  "path": "/realtime/:category?",
  "radar": [
    {
      "source": [
        "news.ebc.net.tw/realtime/:category"
      ],
      "target": "/:category"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "東森新聞|即時 - Powered by RSSHub",
      "errorAt": "2026-08-15T07:22:54.842Z",
      "errorMessage": "200 ",
      "id": "105752020320057344",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://news.ebc.net.tw/realtime/politics",
      "title": "東森新聞|即時",
      "type": "feed",
      "url": "rsshub://ebc/realtime/politics"
    },
    {
      "description": "東森新聞|即時 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "105751285441409024",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://news.ebc.net.tw/realtime",
      "title": "東森新聞|即時",
      "type": "feed",
      "url": "rsshub://ebc/realtime"
    }
  ]
}
```
