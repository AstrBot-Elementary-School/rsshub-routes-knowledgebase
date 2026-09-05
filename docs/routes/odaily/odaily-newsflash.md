# Odaily 星球日报 - 快讯

## Coverage
`index-only`

## Route
- Namespace: `odaily`
- Namespace Name: `Odaily 星球日报`
- Route Path: `/odaily/newsflash`
- Route Name: `快讯`
- Example: `/odaily/newsflash`
- URL: `0daily.com/newsflash`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `newsflash.ts`
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
  - `0daily.com/newsflash`
  - `0daily.com/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/odaily/newsflash",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 361,
  "location": "newsflash.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "快讯",
  "parameters": {},
  "path": "/newsflash",
  "radar": [
    {
      "source": [
        "0daily.com/newsflash",
        "0daily.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "快讯 - Odaily星球日报 - Powered by RSSHub",
      "errorAt": "2025-07-24T19:45:12.725Z",
      "errorMessage": "[GET] \"https://www.odaily.news/api/pp/api/info-flow/newsflash_columns/newsflashes?b_id=&per_page=100\": 404 \n[GET] \"https://www.odaily.news/api/pp/api/info-flow/newsflash_columns/newsflashes?b_id=&per_page=100\": 404 Not Found\n[GET] \"https://www.odaily.news/api/pp/api/info-flow/newsflash_columns/newsflashes?b_id=&per_page=100\": 404 Not Found\n",
      "id": "41572238273905688",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.odaily.news/newsflash",
      "title": "快讯 - Odaily星球日报",
      "type": "feed",
      "url": "rsshub://odaily/newsflash"
    }
  ],
  "url": "0daily.com/newsflash"
}
```
