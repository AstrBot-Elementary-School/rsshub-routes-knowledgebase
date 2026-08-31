# jable - Jable 搜索结果

## Coverage
`index-only`

## Route
- Namespace: `jable`
- Namespace Name: `jable`
- Route Path: `/jable/search/:query`
- Route Name: `Jable 搜索结果`
- Example: `/jable/search/みなみ羽琉`
- URL: `jable.tv`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `eve2ptp`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `query`: Search keyword


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `jable.tv/search/:query`
- `target`: `/search/:query`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/jable/search/みなみ羽琉",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "eve2ptp"
  ],
  "name": "Jable 搜索结果",
  "parameters": {
    "query": "Search keyword"
  },
  "path": "/search/:query",
  "radar": [
    {
      "source": [
        "jable.tv/search/:query"
      ],
      "target": "/search/:query"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
