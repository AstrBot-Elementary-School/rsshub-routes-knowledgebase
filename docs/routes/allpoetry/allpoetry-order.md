# All Poetry - Poems

## Coverage
`index-only`

## Route
- Namespace: `allpoetry`
- Namespace Name: `All Poetry`
- Route Path: `/allpoetry/:order?`
- Route Name: `Poems`
- Example: `/allpoetry/newest`
- URL: `allpoetry.com`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `HenryQW`
- Source Location: `order.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `order`: Ordering, `newest`, `famous` or `picks`, `newest` by default


## Features
- `requirePuppeteer`: true
- `antiCrawler`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/allpoetry/newest",
  "features": {
    "antiCrawler": true,
    "requirePuppeteer": true
  },
  "heat": 0,
  "location": "order.ts",
  "maintainers": [
    "HenryQW"
  ],
  "name": "Poems",
  "parameters": {
    "order": "Ordering, `newest`, `famous` or `picks`, `newest` by default"
  },
  "path": "/:order?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
