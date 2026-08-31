# ShopBack - Store

## Coverage
`index-only`

## Route
- Namespace: `shopback`
- Namespace Name: `ShopBack`
- Route Path: `/shopback/:store`
- Route Name: `Store`
- Example: `/shopback/shopee-mart`
- URL: `shopback.com.tw`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `nczitzk`
- Source Location: `store.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `store`: Store, can be found in URL


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
  - `shopback.com.tw/:category`
  - `shopback.com.tw/`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "example": "/shopback/shopee-mart",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "store.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Store",
  "parameters": {
    "store": "Store, can be found in URL"
  },
  "path": "/:store",
  "radar": [
    {
      "source": [
        "shopback.com.tw/:category",
        "shopback.com.tw/"
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
