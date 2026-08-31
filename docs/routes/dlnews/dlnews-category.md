# DL NEWS - Latest News

## Coverage
`index-only`

## Route
- Namespace: `dlnews`
- Namespace Name: `DL NEWS`
- Route Path: `/dlnews/:category?`
- Route Name: `Latest News`
- Example: `/dlnews/people-culture`
- URL: `dlnews.com/articles`
- Language: `_None_`
- Categories: `other`
- Maintainers: `Rjnishant530`
- Source Location: `category.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `dlnews.com/articles/:category`
- `target`: `/:category`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/dlnews/people-culture",
  "heat": 0,
  "location": "category.tsx",
  "maintainers": [
    "Rjnishant530"
  ],
  "name": "Latest News",
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "dlnews.com/articles/:category"
      ],
      "target": "/:category"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "dlnews.com/articles"
}
```
