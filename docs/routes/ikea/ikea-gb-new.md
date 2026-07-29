# IKEA - UK - New Product Release

## Coverage
`index-only`

## Route
- Namespace: `ikea`
- Namespace Name: `IKEA`
- Route Path: `/ikea/gb/new`
- Route Name: `UK - New Product Release`
- Example: `/ikea/gb/new`
- URL: `ikea.com/gb/en/new/new-products/`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `HenryQW`
- Source Location: `gb/new.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


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
  - `ikea.com/gb/en/new/new-products/`
  - `ikea.com/`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "example": "/ikea/gb/new",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "gb/new.tsx",
  "maintainers": [
    "HenryQW"
  ],
  "name": "UK - New Product Release",
  "parameters": {},
  "path": "/gb/new",
  "radar": [
    {
      "source": [
        "ikea.com/gb/en/new/new-products/",
        "ikea.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "New products released by IKEA UK. - Powered by RSSHub",
      "errorAt": "2026-07-01T04:14:43.705Z",
      "errorMessage": "[GET] \"https://sik.search.blue.cdtapps.com/gb/en/special/more-products?special=new_product&start=24&end=1172\": 400 Bad Request\n",
      "id": "93829994856769536",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.ikea.com/gb/en/new/new-products/",
      "title": "New Products - Browse All New Furniture & Home Decor - IKEA",
      "type": "feed",
      "url": "rsshub://ikea/gb/new"
    }
  ],
  "url": "ikea.com/gb/en/new/new-products/"
}
```
