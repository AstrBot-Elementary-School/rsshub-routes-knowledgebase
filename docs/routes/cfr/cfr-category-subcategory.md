# Council on Foreign Relations - News

## Coverage
`index-only`

## Route
- Namespace: `cfr`
- Namespace Name: `Council on Foreign Relations`
- Route Path: `/cfr/:category/:subCategory?`
- Route Name: `News`
- Example: `/cfr/asia`
- URL: `www.cfr.org`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `KarasuShin`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: category, find it in the URL
- `subCategory`: sub-category, find it in the URL


## Features
- `antiCrawler`: true

## Radar
### Rule 1
- `source`:
  - `www.cfr.org/:category`
  - `www.cfr.org/:category/:subCategory`
- `target`: `/:category/:subCategory?`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/cfr/asia",
  "features": {
    "antiCrawler": true
  },
  "heat": 24,
  "location": "index.ts",
  "maintainers": [
    "KarasuShin"
  ],
  "name": "News",
  "parameters": {
    "category": "category, find it in the URL",
    "subCategory": "sub-category, find it in the URL"
  },
  "path": "/:category/:subCategory?",
  "radar": [
    {
      "source": [
        "www.cfr.org/:category",
        "www.cfr.org/:category/:subCategory"
      ],
      "target": "/:category/:subCategory?"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Asia - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "58007926096163902",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.cfr.org/asia",
      "title": "Asia",
      "type": "feed",
      "url": "rsshub://cfr/asia"
    },
    {
      "description": "Latest Commentary - Powered by RSSHub",
      "errorAt": "2026-01-23T12:46:49.932Z",
      "errorMessage": "[GET] \"https://www.cfr.org/articles/at-october-7-anniversary-israelis-face-an-election-and-an-unfinished-reckoning\": 429 Too Many Requests\n",
      "id": "176857304598777856",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.cfr.org/blog",
      "title": "Latest Commentary",
      "type": "feed",
      "url": "rsshub://cfr/blog"
    }
  ]
}
```
