# Crossbell - Feeds of following

## Coverage
`index-only`

## Route
- Namespace: `crossbell`
- Namespace Name: `Crossbell`
- Route Path: `/crossbell/feeds/following/:characterId`
- Route Name: `Feeds of following`
- Example: `/crossbell/feeds/following/10`
- URL: `crossbell.io`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `DIYgod`
- Source Location: `feeds/following.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `characterId`: N


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
    "social-media"
  ],
  "example": "/crossbell/feeds/following/10",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "feeds/following.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "Feeds of following",
  "parameters": {
    "characterId": "N"
  },
  "path": "/feeds/following/:characterId",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Crossbell Feeds of 10 - Powered by RSSHub",
      "errorAt": "2026-01-27T13:56:45.470Z",
      "errorMessage": "[GET] \"https://indexer.crossbell.io/v1/characters/10/feed/follow\": <no response> fetch failed\n",
      "id": "61267439081640960",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://crossbell.io/",
      "title": "Crossbell Feeds of 10",
      "type": "feed",
      "url": "rsshub://crossbell/feeds/following/10"
    }
  ]
}
```
