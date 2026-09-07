# Shopify - App store search

## Coverage
`index-only`

## Route
- Namespace: `shopify`
- Namespace Name: `Shopify`
- Route Path: `/shopify/apps/search/:q`
- Route Name: `App store search`
- Example: `/shopify/apps/search/flow`
- URL: `shopify.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `PrintNow`
- Source Location: `apps/search.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `q`: 需要搜索的 App


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `apps.shopify.com/search`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/shopify/apps/search/flow",
  "heat": 0,
  "location": "apps/search.ts",
  "maintainers": [
    "PrintNow"
  ],
  "name": "App store search",
  "parameters": {
    "q": "需要搜索的 App"
  },
  "path": "/apps/search/:q",
  "radar": [
    {
      "source": [
        "apps.shopify.com/search"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
