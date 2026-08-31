# BFL AI - Announcements

## Coverage
`index-only`

## Route
- Namespace: `bfl`
- Namespace Name: `BFL AI`
- Route Path: `/bfl/announcements`
- Route Name: `Announcements`
- Example: `/bfl/announcements`
- URL: `bfl.ai/announcements`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `thirteenkai`
- Source Location: `announcements.ts`
- Source Module: `_None_`

## Description
Fetches the latest announcements from Black Forest Labs (bfl.ai). Provides full article content by default with caching.

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
  - `bfl.ai/announcements`
- `target`: `/announcements`
- `title`: `Announcements`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "Fetches the latest announcements from Black Forest Labs (bfl.ai). Provides full article content by default with caching.",
  "example": "/bfl/announcements",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 13,
  "location": "announcements.ts",
  "maintainers": [
    "thirteenkai"
  ],
  "name": "Announcements",
  "parameters": {},
  "path": "/announcements",
  "radar": [
    {
      "source": [
        "bfl.ai/announcements"
      ],
      "target": "/announcements",
      "title": "Announcements"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Amazing AI models from the Black Forest. - Powered by RSSHub",
      "errorAt": "2025-08-14T22:53:13.018Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "153814816828039168",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bfl.ai/announcements",
      "title": "Black Forest Labs - Frontier AI Lab",
      "type": "feed",
      "url": "rsshub://bfl/announcements"
    }
  ],
  "url": "bfl.ai/announcements"
}
```
