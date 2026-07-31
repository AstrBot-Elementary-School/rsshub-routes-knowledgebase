# ACG Vinyl - 黑胶 - News

## Coverage
`index-only`

## Route
- Namespace: `acgvinyl`
- Namespace Name: `ACG Vinyl - 黑胶`
- Route Path: `/acgvinyl/news`
- Route Name: `News`
- Example: `/acgvinyl/news`
- URL: `www.acgvinyl.com/col.jsp?id=103`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `williamgateszhao`
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
  - `www.acgvinyl.com`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/acgvinyl/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 8,
  "location": "news.ts",
  "maintainers": [
    "williamgateszhao"
  ],
  "name": "News",
  "path": "/news",
  "radar": [
    {
      "source": [
        "www.acgvinyl.com"
      ],
      "target": "/news"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "ACG Vinyl - 黑胶 - 黑胶新闻 - Powered by RSSHub",
      "errorAt": "2026-06-15T16:08:13.332Z",
      "errorMessage": "Unexpected end of JSON input\n",
      "id": "190228194247987200",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.acgvinyl.com/col.jsp?id=103",
      "title": "ACG Vinyl - 黑胶 - 黑胶新闻",
      "type": "feed",
      "url": "rsshub://acgvinyl/news"
    }
  ],
  "url": "www.acgvinyl.com/col.jsp?id=103",
  "zh": {
    "name": "黑胶新闻"
  }
}
```
