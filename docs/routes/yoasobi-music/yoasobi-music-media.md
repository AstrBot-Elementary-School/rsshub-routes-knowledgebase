# Yoasobi Official - Media

## Coverage
`index-only`

## Route
- Namespace: `yoasobi-music`
- Namespace Name: `Yoasobi Official`
- Route Path: `/yoasobi-music/media`
- Route Name: `Media`
- Example: `/yoasobi-music/media`
- URL: `www.yoasobi-music.jp/`
- Language: `_None_`
- Categories: `live`
- Maintainers: `Kiotlin`
- Source Location: `media.tsx`
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
  - `www.yoasobi-music.jp/`
  - `www.yoasobi-music.jp/media`

## Raw JSON
```json
{
  "categories": [
    "live"
  ],
  "example": "/yoasobi-music/media",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 5,
  "location": "media.tsx",
  "maintainers": [
    "Kiotlin"
  ],
  "name": "Media",
  "parameters": {},
  "path": "/media",
  "radar": [
    {
      "source": [
        "www.yoasobi-music.jp/",
        "www.yoasobi-music.jp/media"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "YOASOBI's Latest Media - Powered by RSSHub",
      "errorAt": "2025-04-29T22:43:35.597Z",
      "errorMessage": "Failed to convert jsonp to json. Cannot read properties of undefined (reading 'indexOf')\n",
      "id": "59198910903209984",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.yoasobi-music.jp/media",
      "title": "LATEST MEDIA",
      "type": "feed",
      "url": "rsshub://yoasobi-music/media"
    }
  ],
  "url": "www.yoasobi-music.jp/"
}
```
