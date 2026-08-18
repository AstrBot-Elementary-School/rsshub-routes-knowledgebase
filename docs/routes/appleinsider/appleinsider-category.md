# AppleInsider - Category

## Coverage
`index-only`

## Route
- Namespace: `appleinsider`
- Namespace Name: `AppleInsider`
- Route Path: `/appleinsider/:category?`
- Route Name: `Category`
- Example: `/appleinsider`
- URL: `appleinsider.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| News | Reviews | How-tos |
| ---- | ------- | ------- |
|      | reviews | how-to  |

## Parameters
- `category`: Category, see below, News by default


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
  - `appleinsider.com/:category`
  - `appleinsider.com/`
- `target`: `/:category`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| News | Reviews | How-tos |\n| ---- | ------- | ------- |\n|      | reviews | how-to  |",
  "example": "/appleinsider",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 192,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Category",
  "parameters": {
    "category": "Category, see below, News by default"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "appleinsider.com/:category",
        "appleinsider.com/"
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
      "description": "Apple News, Rumors, Reviews, Prices & Deals | AppleInsider - Powered by RSSHub",
      "errorAt": "2025-07-09T04:00:55.913Z",
      "errorMessage": "[GET] \"https://appleinsider.com\": 403 Forbidden\n",
      "id": "55305053541267456",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://appleinsider.com/",
      "title": "Apple News, Rumors, Reviews, Prices & Deals | AppleInsider",
      "type": "feed",
      "url": "rsshub://appleinsider"
    },
    {
      "description": "Latest Apple and Device Reviews | AppleInsider - Powered by RSSHub",
      "errorAt": "2025-07-09T03:19:01.978Z",
      "errorMessage": "[GET] \"https://appleinsider.com/reviews\": 403 Forbidden\n",
      "id": "69569955431876608",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://appleinsider.com/reviews",
      "title": "Latest Apple and Device Reviews | AppleInsider",
      "type": "feed",
      "url": "rsshub://appleinsider/reviews"
    }
  ]
}
```
