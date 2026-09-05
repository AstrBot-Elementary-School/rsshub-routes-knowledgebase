# Free Computer Books - Book List

## Coverage
`index-only`

## Route
- Namespace: `freecomputerbooks`
- Namespace Name: `Free Computer Books`
- Route Path: `/freecomputerbooks/:category?`
- Route Name: `Book List`
- Example: `/freecomputerbooks/compscAlgorithmBooks`
- URL: `freecomputerbooks.com`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `cubroe`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: A category id., which should be the HTML file name (but **without** the `.html` suffix) in the URL path of a book list page.


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `freecomputerbooks.com/`
  - `freecomputerbooks.com/index.html`
- `target`: ``

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/freecomputerbooks/compscAlgorithmBooks",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 261,
  "location": "index.tsx",
  "maintainers": [
    "cubroe"
  ],
  "name": "Book List",
  "parameters": {
    "category": "A category id., which should be the HTML file name (but **without** the `.html` suffix) in the URL path of a book list page."
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "freecomputerbooks.com/",
        "freecomputerbooks.com/index.html"
      ],
      "target": ""
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Free Computer, Programming, Mathematics, Technical Books, Lecture Notes and Tutorials - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "62187667731240962",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://freecomputerbooks.com/",
      "title": "Free Computer Books - Selected New Books",
      "type": "feed",
      "url": "rsshub://freecomputerbooks"
    },
    {
      "description": "Algorithms and Data Structures - Free Computer, Programming, Mathematics, Technical Books, Lecture Notes and Tutorials - Powered by RSSHub",
      "errorAt": "2026-07-07T00:02:17.573Z",
      "errorMessage": "[GET] \"https://freecomputerbooks.com/Planning-Algorithms-1.html\": 404 Not Found\n",
      "id": "59843947513404416",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://freecomputerbooks.com/compscAlgorithmBooks.html",
      "title": "Free Computer Books - Algorithms and Data Structures",
      "type": "feed",
      "url": "rsshub://freecomputerbooks/compscAlgorithmBooks"
    }
  ],
  "url": "freecomputerbooks.com"
}
```
