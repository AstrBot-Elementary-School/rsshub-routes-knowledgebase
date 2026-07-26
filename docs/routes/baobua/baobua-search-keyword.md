# BaoBua - Search

## Coverage
`index-only`

## Route
- Namespace: `baobua`
- Namespace Name: `BaoBua`
- Route Path: `/baobua/search/:keyword`
- Route Name: `Search`
- Example: `/baobua/search/cos`
- URL: `baobua.com/`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `AiraNadih`
- Source Location: `search.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `keyword`: Keyword


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
  - `baobua.com/search`
- `target`: `/search/:keyword`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/baobua/search/cos",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 12,
  "location": "search.ts",
  "maintainers": [
    "AiraNadih"
  ],
  "name": "Search",
  "parameters": {
    "keyword": "Keyword"
  },
  "path": "/search/:keyword",
  "radar": [
    {
      "source": [
        "baobua.com/search"
      ],
      "target": "/search/:keyword"
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "BaoBua - Search: cos - Powered by RSSHub",
      "errorAt": "2025-09-16T08:49:09.640Z",
      "errorMessage": "Unexpected end of JSON input\n",
      "id": "131498387978345472",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://baobua.com/search?q=cos",
      "title": "BaoBua - Search: cos",
      "type": "feed",
      "url": "rsshub://baobua/search/cos"
    }
  ],
  "url": "baobua.com/"
}
```
