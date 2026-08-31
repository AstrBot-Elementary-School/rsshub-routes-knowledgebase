# BBC News Labs - News

## Coverage
`index-only`

## Route
- Namespace: `bbcnewslabs`
- Namespace Name: `BBC News Labs`
- Route Path: `/bbcnewslabs/news`
- Route Name: `News`
- Example: `/bbcnewslabs/news`
- URL: `bbcnewslabs.co.uk/`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `elxy`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `bbcnewslabs.co.uk/`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/bbcnewslabs/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "elxy"
  ],
  "name": "News",
  "parameters": {},
  "path": "/news",
  "radar": [
    {
      "source": [
        "bbcnewslabs.co.uk/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "bbcnewslabs.co.uk/"
}
```
