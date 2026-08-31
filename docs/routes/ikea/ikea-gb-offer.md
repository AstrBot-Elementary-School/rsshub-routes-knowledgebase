# IKEA - UK - Offers

## Coverage
`index-only`

## Route
- Namespace: `ikea`
- Namespace Name: `IKEA`
- Route Path: `/ikea/gb/offer`
- Route Name: `UK - Offers`
- Example: `/ikea/gb/offer`
- URL: `ikea.com/gb/en/offers`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `HenryQW`
- Source Location: `gb/offer.ts`
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
  - `ikea.com/gb/en/offers`
  - `ikea.com/`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "example": "/ikea/gb/offer",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "gb/offer.ts",
  "maintainers": [
    "HenryQW"
  ],
  "name": "UK - Offers",
  "parameters": {},
  "path": "/gb/offer",
  "radar": [
    {
      "source": [
        "ikea.com/gb/en/offers",
        "ikea.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "ikea.com/gb/en/offers"
}
```
