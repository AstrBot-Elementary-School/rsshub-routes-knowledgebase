# Odaily 星球日报 - 搜索快讯

## Coverage
`index-only`

## Route
- Namespace: `odaily`
- Namespace Name: `Odaily 星球日报`
- Route Path: `/odaily/search/news/:keyword`
- Route Name: `搜索快讯`
- Example: `/odaily/search/news/RSS3`
- URL: `odaily.news`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `snowraincloud`
- Source Location: `search-news.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `keyword`: 搜索关键字


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
  - `0daily.com/search/:keyword`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/odaily/search/news/RSS3",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 4,
  "location": "search-news.ts",
  "maintainers": [
    "snowraincloud"
  ],
  "name": "搜索快讯",
  "parameters": {
    "keyword": "搜索关键字"
  },
  "path": "/search/news/:keyword",
  "radar": [
    {
      "source": [
        "0daily.com/search/:keyword"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "快讯 - Odaily星球日报 - Powered by RSSHub",
      "errorAt": "2025-07-24T19:42:47.572Z",
      "errorMessage": "Cannot read properties of undefined (reading 'items')\n",
      "id": "63206794603392000",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.odaily.news/search/RSS3",
      "title": "快讯 - Odaily星球日报",
      "type": "feed",
      "url": "rsshub://odaily/search/news/RSS3"
    },
    {
      "description": "快讯 - Odaily星球日报 - Powered by RSSHub",
      "errorAt": "2025-07-24T20:03:50.475Z",
      "errorMessage": "Cannot read properties of undefined (reading 'items')\n",
      "id": "98041370543268864",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.odaily.news/search/AI%20Agent",
      "title": "快讯 - Odaily星球日报",
      "type": "feed",
      "url": "rsshub://odaily/search/news/AI%20Agent"
    }
  ]
}
```
