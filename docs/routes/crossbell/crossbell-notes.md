# Crossbell - Notes

## Coverage
`index-only`

## Route
- Namespace: `crossbell`
- Namespace Name: `Crossbell`
- Route Path: `/crossbell/notes`
- Route Name: `Notes`
- Example: `/crossbell/notes`
- URL: `crossbell.io/*`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `DIYgod`
- Source Location: `notes/index.ts`
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
  - `crossbell.io/*`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/crossbell/notes",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "notes/index.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "Notes",
  "parameters": {},
  "path": "/notes",
  "radar": [
    {
      "source": [
        "crossbell.io/*"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Crossbell Notes - Powered by RSSHub",
      "errorAt": "2026-01-27T09:38:45.841Z",
      "errorMessage": "[GET] \"https://indexer.crossbell.io/v1/notes?includeCharacter=true\": <no response> fetch failed (Connect Timeout Error (attempted address: indexer.crossbell.io:443, timeout: 10000ms))\n",
      "id": "72809817072434176",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://crossbell.io/",
      "title": "Crossbell Notes",
      "type": "feed",
      "url": "rsshub://crossbell/notes"
    }
  ],
  "url": "crossbell.io/*"
}
```
