# IPSW.dev - Apple latest beta firmware

## Coverage
`index-only`

## Route
- Namespace: `ipsw.dev`
- Namespace Name: `IPSW.dev`
- Route Path: `/ipsw.dev/index/:productID`
- Route Name: `Apple latest beta firmware`
- Example: `/ipsw.dev/index/iPhone16,1`
- URL: `ipsw.dev`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `RieN7`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `productID`: Product ID


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/ipsw.dev/index/iPhone16,1",
  "heat": 8,
  "location": "index.tsx",
  "maintainers": [
    "RieN7"
  ],
  "name": "Apple latest beta firmware",
  "parameters": {
    "productID": "Product ID"
  },
  "path": "/index/:productID",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Released - Powered by RSSHub",
      "errorAt": "2025-10-29T13:40:42.048Z",
      "errorMessage": "[GET] \"https://ipsw.dev/product/version/iPhone16,1\": 403 Forbidden\n",
      "id": "74985463608419328",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://ipsw.dev/product/version/iPhone16,1",
      "title": "Released",
      "type": "feed",
      "url": "rsshub://ipsw.dev/index/iPhone16,1"
    },
    {
      "description": "Released - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "168663519061177344",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://ipsw.dev/product/version/iPhone17,1",
      "title": "Released",
      "type": "feed",
      "url": "rsshub://ipsw.dev/index/iPhone17%2C1"
    }
  ]
}
```
