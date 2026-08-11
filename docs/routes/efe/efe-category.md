# EFE Noticias - Category

## Coverage
`index-only`

## Route
- Namespace: `efe`
- Namespace Name: `EFE Noticias`
- Route Path: `/efe/:category?`
- Route Name: `Category`
- Example: `/efe/mundo`
- URL: `efe.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `mlkgrnt`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: {"default": "mundo", "description": "Category slug, see table below. Defaults to mundo."}


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
  - `efe.com/:category`
- `target`: `/:category`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/efe/mundo",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "mlkgrnt"
  ],
  "name": "Category",
  "parameters": {
    "category": {
      "default": "mundo",
      "description": "Category slug, see table below. Defaults to mundo."
    }
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "efe.com/:category"
      ],
      "target": "/:category"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
