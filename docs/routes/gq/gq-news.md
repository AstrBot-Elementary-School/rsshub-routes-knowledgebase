# GQ - News

## Coverage
`index-only`

## Route
- Namespace: `gq`
- Namespace Name: `GQ`
- Route Path: `/gq/news`
- Route Name: `News`
- Example: `/gq/news`
- URL: `gq.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `IvanWng97`
- Source Location: `news.ts`
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
  - `gq.com/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/gq/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 553,
  "location": "news.ts",
  "maintainers": [
    "IvanWng97"
  ],
  "name": "News",
  "parameters": {},
  "path": "/news",
  "radar": [
    {
      "source": [
        "gq.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "GQ is the global flagship of men's fashion, the arbiter of cool for anyone who sees the world through the lens of taste and style. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "57995444932781056",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.gq.com/",
      "title": "GQ",
      "type": "feed",
      "url": "rsshub://gq/news"
    }
  ],
  "view": 0
}
```
