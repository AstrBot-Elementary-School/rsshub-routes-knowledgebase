# EZTV - Lookup Torrents by IMDB ID

## Coverage
`index-only`

## Route
- Namespace: `eztv`
- Namespace Name: `EZTV`
- Route Path: `/eztv/torrents/:imdb_id`
- Route Name: `Lookup Torrents by IMDB ID`
- Example: `/eztv/torrents/6048596`
- URL: `eztv.it`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `Songkeys`
- Source Location: `imdb.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `imdb_id`: The IMDB ID corresponding to the seed of show you want to search can be found on the official website [IMDB](https://www.imdb.com)


## Features
- `antiCrawler`: true
- `supportBT`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/eztv/torrents/6048596",
  "features": {
    "antiCrawler": true,
    "supportBT": true
  },
  "heat": 0,
  "location": "imdb.ts",
  "maintainers": [
    "Songkeys"
  ],
  "name": "Lookup Torrents by IMDB ID",
  "parameters": {
    "imdb_id": "The IMDB ID corresponding to the seed of show you want to search can be found on the official website [IMDB](https://www.imdb.com)"
  },
  "path": "/torrents/:imdb_id",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
