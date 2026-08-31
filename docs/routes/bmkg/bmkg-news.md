# BADAN METEOROLOGI, KLIMATOLOGI, DAN GEOFISIKA(Indonesian) - News

## Coverage
`index-only`

## Route
- Namespace: `bmkg`
- Namespace Name: `BADAN METEOROLOGI, KLIMATOLOGI, DAN GEOFISIKA(Indonesian)`
- Route Path: `/bmkg/news`
- Route Name: `News`
- Example: `/bmkg/news`
- URL: `bmkg.go.id/`
- Language: `_None_`
- Categories: `forecast`
- Maintainers: `Shinanory`
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
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `bmkg.go.id/`
  - `bmkg.go.id/berita`

## Raw JSON
```json
{
  "categories": [
    "forecast"
  ],
  "example": "/bmkg/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "news.ts",
  "maintainers": [
    "Shinanory"
  ],
  "name": "News",
  "parameters": {},
  "path": "/news",
  "radar": [
    {
      "source": [
        "bmkg.go.id/",
        "bmkg.go.id/berita"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "印尼气象气候和地球物理局 新闻 | BMKG news - Powered by RSSHub",
      "errorAt": "2024-12-16T06:04:27.800Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "54123126710461440",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.bmkg.go.id/",
      "title": "BMKG | Badan Meteorologi, Klimatologi, dan Geofisika",
      "type": "feed",
      "url": "rsshub://bmkg/news"
    }
  ],
  "url": "bmkg.go.id/"
}
```
