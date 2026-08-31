# Patagonia - New Arrivals

## Coverage
`index-only`

## Route
- Namespace: `patagonia`
- Namespace Name: `Patagonia`
- Route Path: `/patagonia/new-arrivals/:category`
- Route Name: `New Arrivals`
- Example: `/patagonia/new-arrivals/mens`
- URL: `patagonia.com`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `IvanWng97`
- Source Location: `new-arrivals.tsx`
- Source Module: `_None_`

## Description
| Men's | Women's | Kids' & Baby | Packs & Gear |
| ----- | ------- | ------------ | ------------ |
| mens  | womens  | kids         | luggage      |

## Parameters
- `category`: category, see below


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
  "description": "| Men's | Women's | Kids' & Baby | Packs & Gear |\n| ----- | ------- | ------------ | ------------ |\n| mens  | womens  | kids         | luggage      |",
  "example": "/patagonia/new-arrivals/mens",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 8,
  "location": "new-arrivals.tsx",
  "maintainers": [
    "IvanWng97"
  ],
  "name": "New Arrivals",
  "parameters": {
    "category": "category, see below"
  },
  "path": "/new-arrivals/:category",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Patagonia - New Arrivals - MENS - Powered by RSSHub",
      "errorAt": "2025-06-25T20:58:11.937Z",
      "errorMessage": "Cannot read properties of undefined (reading 'product_name')\n",
      "id": "82011783614632960",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.patagonia.com/shop/mens-new-arrivals",
      "title": "Patagonia - New Arrivals - MENS",
      "type": "feed",
      "url": "rsshub://patagonia/new-arrivals/mens"
    }
  ]
}
```
