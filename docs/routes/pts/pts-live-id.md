# 公視新聞網 - 整理報導

## Coverage
`index-only`

## Route
- Namespace: `pts`
- Namespace Name: `公視新聞網`
- Route Path: `/pts/live/:id`
- Route Name: `整理報導`
- Example: `/pts/live/62e8e4bbb4de2cbd74468b2b`
- URL: `news.pts.org.tw`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `live.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 報導 id，可在对应整理報導页 URL 中找到


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
  - `news.pts.org.tw/live/:id`
  - `news.pts.org.tw/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/pts/live/62e8e4bbb4de2cbd74468b2b",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "live.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "整理報導",
  "parameters": {
    "id": "報導 id，可在对应整理報導页 URL 中找到"
  },
  "path": "/live/:id",
  "radar": [
    {
      "source": [
        "news.pts.org.tw/live/:id",
        "news.pts.org.tw/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
