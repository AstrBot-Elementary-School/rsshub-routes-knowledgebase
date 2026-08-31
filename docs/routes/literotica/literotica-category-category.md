# Literotica - Category

## Coverage
`index-only`

## Route
- Namespace: `literotica`
- Namespace Name: `Literotica`
- Route Path: `/literotica/category/:category`
- Route Name: `Category`
- Example: `/literotica/category/anal-sex-stories`
- URL: `literotica.com`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `nczitzk`
- Source Location: `category.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: Category, can be found in URL


## Features
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `literotica.com/c/:category`
  - `literotica.com/`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/literotica/category/anal-sex-stories",
  "features": {
    "nsfw": true
  },
  "heat": 0,
  "location": "category.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Category",
  "parameters": {
    "category": "Category, can be found in URL"
  },
  "path": "/category/:category",
  "radar": [
    {
      "source": [
        "literotica.com/c/:category",
        "literotica.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
