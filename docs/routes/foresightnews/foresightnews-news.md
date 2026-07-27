# Foresight News - 快讯

## Coverage
`index-only`

## Route
- Namespace: `foresightnews`
- Namespace Name: `Foresight News`
- Route Path: `/foresightnews/news`
- Route Name: `快讯`
- Example: `/foresightnews/news`
- URL: `foresightnews.pro/news`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
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
  - `foresightnews.pro/news`
  - `foresightnews.pro/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/foresightnews/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 246,
  "location": "news.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "快讯",
  "parameters": {},
  "path": "/news",
  "radar": [
    {
      "source": [
        "foresightnews.pro/news",
        "foresightnews.pro/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "快讯 - Foresight News - Powered by RSSHub",
      "errorAt": "2026-03-25T12:04:05.238Z",
      "errorMessage": "[GET] \"https://api.foresightnews.pro/v1/news?size=50\": 403 Forbidden\n[GET] \"https://api.foresightnews.pro/v1/news?size=50\": 403 Forbidden\n[GET] \"https://api.foresightnews.pro/v1/news?size=50\": 403 Forbidden\n",
      "id": "41756176414118912",
      "image": "https://img.foresightnews.pro/vertical_logo.png",
      "ownerUserId": null,
      "siteUrl": "https://foresightnews.pro/news",
      "title": "Foresight News - 快讯",
      "type": "feed",
      "url": "rsshub://foresightnews/news"
    }
  ],
  "url": "foresightnews.pro/news"
}
```
