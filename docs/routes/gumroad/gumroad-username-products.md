# Gumroad - Products

## Coverage
`index-only`

## Route
- Namespace: `gumroad`
- Namespace Name: `Gumroad`
- Route Path: `/gumroad/:username/:products`
- Route Name: `Products`
- Example: `/gumroad/afkmaster/Eve10`
- URL: `gumroad.com`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `Fatpandac`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
`https://afkmaster.gumroad.com/l/Eve10` -> `/gumroad/afkmaster/Eve10`

## Parameters
- `username`: username, can be found in URL
- `products`: products name, can be found in URL


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
    "shopping"
  ],
  "description": "`https://afkmaster.gumroad.com/l/Eve10` -> `/gumroad/afkmaster/Eve10`",
  "example": "/gumroad/afkmaster/Eve10",
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
  "name": "Products",
  "parameters": {
    "products": "products name, can be found in URL",
    "username": "username, can be found in URL"
  },
  "path": "/:username/:products",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
