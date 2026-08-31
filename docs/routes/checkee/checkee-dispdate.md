# checkee.info - US Visa check status

## Coverage
`index-only`

## Route
- Namespace: `checkee`
- Namespace Name: `checkee.info`
- Route Path: `/checkee/:dispdate`
- Route Name: `US Visa check status`
- Example: `/checkee/2019-03`
- URL: `www.checkee.info`
- Language: `_None_`
- Categories: `other`
- Maintainers: `lalxyy`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `dispdate`: Year-month of visa check，for example 2019-03


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/checkee/2019-03",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "lalxyy"
  ],
  "name": "US Visa check status",
  "parameters": {
    "dispdate": "Year-month of visa check，for example 2019-03"
  },
  "path": "/:dispdate",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
