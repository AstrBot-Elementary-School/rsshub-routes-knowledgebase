# Crossbell - Notes of source

## Coverage
`index-only`

## Route
- Namespace: `crossbell`
- Namespace Name: `Crossbell`
- Route Path: `/crossbell/notes/source/:source`
- Route Name: `Notes of source`
- Example: `/crossbell/notes/source/xlog`
- URL: `crossbell.io/*`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `DIYgod`
- Source Location: `notes/source.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `source`: N


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
  - `crossbell.io/*`
- `target`: `/notes`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/crossbell/notes/source/xlog",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "notes/source.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "Notes of source",
  "parameters": {
    "source": "N"
  },
  "path": "/notes/source/:source",
  "radar": [
    {
      "source": [
        "crossbell.io/*"
      ],
      "target": "/notes"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Crossbell Notes from xlog - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "60328418018263040",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://crossbell.io/",
      "title": "Crossbell Notes from xlog",
      "type": "feed",
      "url": "rsshub://crossbell/notes/source/xlog"
    }
  ],
  "url": "crossbell.io/*"
}
```
