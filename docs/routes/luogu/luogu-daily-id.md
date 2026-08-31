# 洛谷 - 日报

## Coverage
`index-only`

## Route
- Namespace: `luogu`
- Namespace Name: `洛谷`
- Route Path: `/luogu/daily/:id?`
- Route Name: `日报`
- Example: `/luogu/daily`
- URL: `luogu.com.cn/discuss/47327`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `LogicJake, prnake, nczitzk`
- Source Location: `daily.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 年度日报所在帖子 id，可在 URL 中找到，不填默认为 `47327`


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
  - `luogu.com.cn/discuss/47327`
  - `luogu.com.cn/`
- `target`: `/daily`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/luogu/daily",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "daily.ts",
  "maintainers": [
    "LogicJake",
    "prnake",
    "nczitzk"
  ],
  "name": "日报",
  "parameters": {
    "id": "年度日报所在帖子 id，可在 URL 中找到，不填默认为 `47327`"
  },
  "path": "/daily/:id?",
  "radar": [
    {
      "source": [
        "luogu.com.cn/discuss/47327",
        "luogu.com.cn/"
      ],
      "target": "/daily"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "luogu.com.cn/discuss/47327"
}
```
