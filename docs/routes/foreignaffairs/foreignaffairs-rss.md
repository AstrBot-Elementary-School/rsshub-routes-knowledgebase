# Foreign Affairs - RSS

## Coverage
`index-only`

## Route
- Namespace: `foreignaffairs`
- Namespace Name: `Foreign Affairs`
- Route Path: `/foreignaffairs/rss`
- Route Name: `RSS`
- Example: `/foreignaffairs/rss`
- URL: `www.foreignaffairs.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `dzx-dzx`
- Source Location: `rss.ts`
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
_None_

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/foreignaffairs/rss",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 195,
  "location": "rss.ts",
  "maintainers": [
    "dzx-dzx"
  ],
  "name": "RSS",
  "parameters": {},
  "path": "/rss",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Foreign Affairs - RSS - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "119928653973749760",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.foreignaffairs.com/rss.xml",
      "title": "Foreign Affairs - RSS",
      "type": "feed",
      "url": "rsshub://foreignaffairs/rss"
    }
  ]
}
```
