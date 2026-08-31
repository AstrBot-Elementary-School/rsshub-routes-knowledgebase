# Bing - 搜索

## Coverage
`index-only`

## Route
- Namespace: `bing`
- Namespace Name: `Bing`
- Route Path: `/bing/search/:keyword`
- Route Name: `搜索`
- Example: `/bing/search/rss`
- URL: `cn.bing.com/`
- Language: `_None_`
- Categories: `other`
- Maintainers: `CaoMeiYouRen`
- Source Location: `search.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `keyword`: 搜索关键词


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
  - `cn.bing.com/`
- `target`: ``

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/bing/search/rss",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "search.ts",
  "maintainers": [
    "CaoMeiYouRen"
  ],
  "name": "搜索",
  "parameters": {
    "keyword": "搜索关键词"
  },
  "path": "/search/:keyword",
  "radar": [
    {
      "source": [
        "cn.bing.com/"
      ],
      "target": ""
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "cn.bing.com/"
}
```
