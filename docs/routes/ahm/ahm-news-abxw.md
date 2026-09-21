# Anhui Museum - 安博新闻

## Coverage
`index-only`

## Route
- Namespace: `ahm`
- Namespace Name: `Anhui Museum`
- Route Path: `/ahm/news/abxw`
- Route Name: `安博新闻`
- Example: `/ahm/news/abxw`
- URL: `www.ahm.cn`
- Language: `_None_`
- Categories: `travel`
- Maintainers: `magazian`
- Source Location: `abxw.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.ahm.cn/News/List/abxw`
- `target`: `/news/abxw`

## Raw JSON
```json
{
  "categories": [
    "travel"
  ],
  "example": "/ahm/news/abxw",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "abxw.ts",
  "maintainers": [
    "magazian"
  ],
  "name": "安博新闻",
  "path": "/news/abxw",
  "radar": [
    {
      "source": [
        "www.ahm.cn/News/List/abxw"
      ],
      "target": "/news/abxw"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
