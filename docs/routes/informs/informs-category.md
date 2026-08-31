# INFORMS - Category

## Coverage
`index-only`

## Route
- Namespace: `informs`
- Namespace Name: `INFORMS`
- Route Path: `/informs/:category?`
- Route Name: `Category`
- Example: `/informs/mnsc`
- URL: `pubsonline.informs.org`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `Fatpandac`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: Category, can be found in the url of the page, `orsc` by default


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "example": "/informs/mnsc",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "index.tsx",
  "maintainers": [
    "Fatpandac"
  ],
  "name": "Category",
  "parameters": {
    "category": "Category, can be found in the url of the page, `orsc` by default"
  },
  "path": "/:category?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
