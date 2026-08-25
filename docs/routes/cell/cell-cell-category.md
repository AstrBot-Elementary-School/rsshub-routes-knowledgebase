# Cell - Current Issue

## Coverage
`index-only`

## Route
- Namespace: `cell`
- Namespace Name: `Cell`
- Route Path: `/cell/cell/:category`
- Route Name: `Current Issue`
- Example: `/cell/cell/current`
- URL: `www.cell.com`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `y9c`
- Source Location: `cell.ts`
- Source Module: `_None_`

## Description
| `:category` |        Query Type       |
| :---------: | :---------------------: |
|   current   | Current Issue (default) |
|   inpress   |    Articles in press    |

## Parameters
- `category`: Query type, see the table below


## Features
- `supportScihub`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "description": "| `:category` |        Query Type       |\n| :---------: | :---------------------: |\n|   current   | Current Issue (default) |\n|   inpress   |    Articles in press    |",
  "example": "/cell/cell/current",
  "features": {
    "supportScihub": true
  },
  "heat": 0,
  "location": "cell.ts",
  "maintainers": [
    "y9c"
  ],
  "name": "Current Issue",
  "parameters": {
    "category": "Query type, see the table below"
  },
  "path": "/cell/:category",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
