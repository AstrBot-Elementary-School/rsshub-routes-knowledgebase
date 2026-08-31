# Kuwait Local - Categorised News

## Coverage
`index-only`

## Route
- Namespace: `kuwaitlocal`
- Namespace Name: `Kuwait Local`
- Route Path: `/kuwaitlocal/:category?`
- Route Name: `Categorised News`
- Example: `/kuwaitlocal/article`
- URL: `kuwaitlocal.com/news/latest`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: Category name, can be found in URL, `latest` by default


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
  - `kuwaitlocal.com/news/categories/:category`
- `target`: `/:category`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/kuwaitlocal/article",
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
    "TonyRL"
  ],
  "name": "Categorised News",
  "parameters": {
    "category": "Category name, can be found in URL, `latest` by default"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "kuwaitlocal.com/news/categories/:category"
      ],
      "target": "/:category"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "kuwaitlocal.com/news/latest"
}
```
