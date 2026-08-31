# Hacking8 - 搜索

## Coverage
`index-only`

## Route
- Namespace: `hacking8`
- Namespace Name: `Hacking8`
- Route Path: `/hacking8/search/:keyword?`
- Route Name: `搜索`
- Example: `/hacking8/search/rsshub`
- URL: `hacking8.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `nczitzk`
- Source Location: `search.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `keyword`: 关键字，默认为空


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
  - `hacking8.com/index/:category`
  - `hacking8.com/`
- `target`: `/:category?`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/hacking8/search/rsshub",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "search.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "搜索",
  "parameters": {
    "keyword": "关键字，默认为空"
  },
  "path": "/search/:keyword?",
  "radar": [
    {
      "source": [
        "hacking8.com/index/:category",
        "hacking8.com/"
      ],
      "target": "/:category?"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
