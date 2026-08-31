# Kelowna Capital News - News

## Coverage
`index-only`

## Route
- Namespace: `kelownacapnews`
- Namespace Name: `Kelowna Capital News`
- Route Path: `/kelownacapnews/:type`
- Route Name: `News`
- Example: `/kelownacapnews/local-news`
- URL: `www.kelownacapnews.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `hualiong`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
`type` is as follows:

| News type     | Value         | News type    | Value        |
| ------------- | ------------- | ------------ | ------------ |
| News          | news          | Sports       | sports       |
| Local News    | local-news    | Business     | business     |
| Canadian News | national-news | Trending Now | trending-now |
| World News    | world-news    | Opinion      | opinion      |
| Entertainment | entertainment |              |              |

## Parameters
- `type`: Type of news


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
  - `www.kelownacapnews.com/:type`
- `target`: `/:type`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "`type` is as follows:\n\n| News type     | Value         | News type    | Value        |\n| ------------- | ------------- | ------------ | ------------ |\n| News          | news          | Sports       | sports       |\n| Local News    | local-news    | Business     | business     |\n| Canadian News | national-news | Trending Now | trending-now |\n| World News    | world-news    | Opinion      | opinion      |\n| Entertainment | entertainment |              |              |",
  "example": "/kelownacapnews/local-news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "hualiong"
  ],
  "name": "News",
  "parameters": {
    "type": "Type of news"
  },
  "path": "/:type",
  "radar": [
    {
      "source": [
        "www.kelownacapnews.com/:type"
      ],
      "target": "/:type"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "www.kelownacapnews.com"
}
```
