# Nature Journal - Nature News

## Coverage
`index-only`

## Route
- Namespace: `nature`
- Namespace Name: `Nature Journal`
- Route Path: `/nature/news`
- Route Name: `Nature News`
- Example: `/nature/news`
- URL: `nature.com/latest-news`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `y9c, TonyRL`
- Source Location: `news.ts`
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
- `supportScihub`: true

## Radar
### Rule 1
- `source`:
  - `nature.com/latest-news`
  - `nature.com/news`
  - `nature.com/`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "example": "/nature/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": true
  },
  "heat": 313,
  "location": "news.ts",
  "maintainers": [
    "y9c",
    "TonyRL"
  ],
  "name": "Nature News",
  "parameters": {},
  "path": "/news",
  "radar": [
    {
      "source": [
        "nature.com/latest-news",
        "nature.com/news",
        "nature.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Browse the latest news from the world's leading research journal. - Powered by RSSHub",
      "errorAt": "2026-06-19T20:42:09.170Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\nthis route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "79390521827702784",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.nature.com/latest-news",
      "title": "Nature | Latest News",
      "type": "feed",
      "url": "rsshub://nature/news"
    }
  ],
  "url": "nature.com/latest-news"
}
```
