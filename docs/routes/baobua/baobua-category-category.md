# BaoBua - Category

## Coverage
`index-only`

## Route
- Namespace: `baobua`
- Namespace Name: `BaoBua`
- Route Path: `/baobua/category/:category`
- Route Name: `Category`
- Example: `/baobua/category/network`
- URL: `baobua.com/`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `AiraNadih`
- Source Location: `category.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: Category


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
  - `baobua.com/cat/:category`
- `target`: `/category/:category`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/baobua/category/network",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 54,
  "location": "category.ts",
  "maintainers": [
    "AiraNadih"
  ],
  "name": "Category",
  "parameters": {
    "category": "Category"
  },
  "path": "/category/:category",
  "radar": [
    {
      "source": [
        "baobua.com/cat/:category"
      ],
      "target": "/category/:category"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "BaoBua - Category: xiuren - Powered by RSSHub",
      "errorAt": "2025-09-16T08:27:34.576Z",
      "errorMessage": "Unexpected end of JSON input\nUnexpected end of JSON input\nUnexpected end of JSON input\n",
      "id": "146189302661421056",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://baobua.com/cat/xiuren/",
      "title": "BaoBua - Category: xiuren",
      "type": "feed",
      "url": "rsshub://baobua/category/xiuren"
    },
    {
      "description": "BaoBua - Category: network - Powered by RSSHub",
      "errorAt": "2025-09-16T09:16:48.457Z",
      "errorMessage": "Unexpected end of JSON input\n",
      "id": "131254379451723776",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://baobua.com/cat/network/",
      "title": "BaoBua - Category: network",
      "type": "feed",
      "url": "rsshub://baobua/category/network"
    }
  ],
  "url": "baobua.com/"
}
```
