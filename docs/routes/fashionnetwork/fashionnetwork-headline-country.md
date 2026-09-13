# FashionNetwork - Headline

## Coverage
`index-only`

## Route
- Namespace: `fashionnetwork`
- Namespace Name: `FashionNetwork`
- Route Path: `/fashionnetwork/headline/:country?`
- Route Name: `Headline`
- Example: `/fashionnetwork/headline`
- URL: `fashionnetwork.cn`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `headline.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `country`: Country, see the News route below, `ww` by default


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/fashionnetwork/headline",
  "heat": 0,
  "location": "headline.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Headline",
  "parameters": {
    "country": "Country, see the News route below, `ww` by default"
  },
  "path": "/headline/:country?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
