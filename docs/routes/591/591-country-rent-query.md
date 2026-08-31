# 591 Rental house - Rental house

## Coverage
`index-only`

## Route
- Namespace: `591`
- Namespace Name: `591 Rental house`
- Route Path: `/591/:country/rent/:query?`
- Route Name: `Rental house`
- Example: `/591/tw/rent/order=posttime&orderType=desc`
- URL: `rent.591.com.tw`
- Language: `_None_`
- Categories: `other`
- Maintainers: `Yukaii`
- Source Location: `list.tsx`
- Source Module: `_None_`

## Description
::: tip
Copy the URL of the 591 filter housing page and remove the front part `https://rent.591.com.tw/?`, you will get the query parameters.
:::

## Parameters
- `country`: Country code. Only tw is supported now
- `query`: Query Parameters


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
    "other"
  ],
  "description": "::: tip\nCopy the URL of the 591 filter housing page and remove the front part `https://rent.591.com.tw/?`, you will get the query parameters.\n:::",
  "example": "/591/tw/rent/order=posttime&orderType=desc",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "list.tsx",
  "maintainers": [
    "Yukaii"
  ],
  "name": "Rental house",
  "parameters": {
    "country": "Country code. Only tw is supported now",
    "query": "Query Parameters"
  },
  "path": "/:country/rent/:query?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
