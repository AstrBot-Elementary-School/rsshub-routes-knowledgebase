# 五大唱片 - 新貨上架

## Coverage
`index-only`

## Route
- Namespace: `5music`
- Namespace Name: `五大唱片`
- Route Path: `/5music/new-releases/:category?`
- Route Name: `新貨上架`
- Example: `/5music/new-releases`
- URL: `www.5music.com.tw/New_releases.asp`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `gideonsenku`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
Categories:

| 華語 | 西洋 | 東洋 | 韓語 | 古典 |
| ---- | ---- | ---- | ---- | ---- |
| A    | B    | F    | M    | D    |

## Parameters
- `category`: Category, see below, defaults to all


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
  - `www.5music.com.tw/New_releases.asp`
  - `www.5music.com.tw/`
- `target`: `/new-releases`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "description": "Categories:\n\n| 華語 | 西洋 | 東洋 | 韓語 | 古典 |\n| ---- | ---- | ---- | ---- | ---- |\n| A    | B    | F    | M    | D    |",
  "example": "/5music/new-releases",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 6,
  "location": "index.ts",
  "maintainers": [
    "gideonsenku"
  ],
  "name": "新貨上架",
  "parameters": {
    "category": "Category, see below, defaults to all"
  },
  "path": "/new-releases/:category?",
  "radar": [
    {
      "source": [
        "www.5music.com.tw/New_releases.asp",
        "www.5music.com.tw/"
      ],
      "target": "/new-releases"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected -10450752203 to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:61:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "五大唱片 - 新货上架 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "125390517764326400",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.5music.com.tw/New_releases.asp?mut=A",
      "title": "五大唱片 - 新货上架",
      "type": "feed",
      "url": "rsshub://5music/new-releases"
    }
  ],
  "url": "www.5music.com.tw/New_releases.asp"
}
```
