# Routledge - Book Series

## Coverage
`index-only`

## Route
- Namespace: `routledge`
- Namespace Name: `Routledge`
- Route Path: `/routledge/:bookName/book-series/:bookId`
- Route Name: `Book Series`
- Example: `/routledge/A-Colour-Atlas/book-series/CRCACOLOATLA`
- URL: `routledge.com`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `TonyRL`
- Source Location: `book-series.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `bookName`: Book name, can be found in URL
- `bookId`: Book ID, can be found in URL


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `routledge.com/:bookName/book-series/:bookId`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "example": "/routledge/A-Colour-Atlas/book-series/CRCACOLOATLA",
  "heat": 0,
  "location": "book-series.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Book Series",
  "parameters": {
    "bookId": "Book ID, can be found in URL",
    "bookName": "Book name, can be found in URL"
  },
  "path": "/:bookName/book-series/:bookId",
  "radar": [
    {
      "source": [
        "routledge.com/:bookName/book-series/:bookId"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected NaN to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:61:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
