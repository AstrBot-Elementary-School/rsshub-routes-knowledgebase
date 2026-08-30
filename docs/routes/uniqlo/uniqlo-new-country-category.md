# Uniqlo - New Arrivals

## Coverage
`index-only`

## Route
- Namespace: `uniqlo`
- Namespace Name: `Uniqlo`
- Route Path: `/uniqlo/new/:country/:category`
- Route Name: `New Arrivals`
- Example: `/uniqlo/new/sg/men`
- URL: `www.uniqlo.com`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `DIYgod`
- Source Location: `new.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `country`: currently only supports sg, us, jp
- `category`: supports `men` `women`, `kids`, `baby`


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
  "example": "/uniqlo/new/sg/men",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 41,
  "location": "new.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "New Arrivals",
  "parameters": {
    "category": "supports `men` `women`, `kids`, `baby`",
    "country": "currently only supports sg, us, jp"
  },
  "path": "/new/:country/:category",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Uniqlo men new arrivals in sg - Powered by RSSHub",
      "errorAt": "2026-06-15T22:48:26.372Z",
      "errorMessage": "[GET] \"https://www.uniqlo.com/sg/api/commerce/v3/en/products?path=5856&flagCodes=salesStart+newSKU,salesStart+newSKU,salesStart+newSKU&sort=1&limit=24&offset=0\": 404 Not Found\n",
      "id": "41147805268337675",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.uniqlo.com/sg/en/feature/new/men",
      "title": "Uniqlo men new arrivals in sg",
      "type": "feed",
      "url": "rsshub://uniqlo/new/sg/men"
    },
    {
      "description": "Uniqlo men new arrivals in us - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "164380886195041280",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.uniqlo.com/us/en/feature/new/men",
      "title": "Uniqlo men new arrivals in us",
      "type": "feed",
      "url": "rsshub://uniqlo/new/us/men"
    }
  ]
}
```
