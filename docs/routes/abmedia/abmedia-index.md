# 链新闻 ABMedia - 首页最新新闻

## Coverage
`index-only`

## Route
- Namespace: `abmedia`
- Namespace Name: `链新闻 ABMedia`
- Route Path: `/abmedia/index`
- Route Name: `首页最新新闻`
- Example: `/abmedia/index`
- URL: `www.abmedia.io/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `Fatpandac`
- Source Location: `index.ts`
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
  - `www.abmedia.io/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/abmedia/index",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 7,
  "location": "index.ts",
  "maintainers": [
    "Fatpandac"
  ],
  "name": "首页最新新闻",
  "parameters": {},
  "path": "/index",
  "radar": [
    {
      "source": [
        "www.abmedia.io/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "ABMedia - 最新消息 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "134802206056046593",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.abmedia.io/",
      "title": "ABMedia - 最新消息",
      "type": "feed",
      "url": "rsshub://abmedia/index"
    }
  ],
  "url": "www.abmedia.io/"
}
```
