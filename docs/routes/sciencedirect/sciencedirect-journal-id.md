# ScienceDirect - Journal

## Coverage
`index-only`

## Route
- Namespace: `sciencedirect`
- Namespace Name: `ScienceDirect`
- Route Path: `/sciencedirect/journal/:id`
- Route Name: `Journal`
- Example: `/sciencedirect/journal/research-policy`
- URL: `sciencedirect.com`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `nczitzk`
- Source Location: `journal.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: Journal id, can be found in URL


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
  - `sciencedirect.com/journal/:id`
  - `sciencedirect.com/`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "example": "/sciencedirect/journal/research-policy",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 6,
  "location": "journal.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Journal",
  "parameters": {
    "id": "Journal id, can be found in URL"
  },
  "path": "/journal/:id",
  "radar": [
    {
      "source": [
        "sciencedirect.com/journal/:id",
        "sciencedirect.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-07-13T06:37:53.133Z",
      "errorMessage": "[GET] \"https://www.sciencedirect.com/journal/progress-in-solid-state-chemistry/articles-in-press\": 400 Bad Request\n",
      "id": "167109692329335818",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://sciencedirect/journal/progress-in-solid-state-chemistry"
    },
    {
      "description": null,
      "errorAt": "2026-06-30T06:05:34.874Z",
      "errorMessage": "[GET] \"https://www.sciencedirect.com/journal/computer-methods-in-applied-mechanics-and-engineering/articles-in-press\": 403 Forbidden\n",
      "id": "1178645011650969617",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://sciencedirect/journal/computer-methods-in-applied-mechanics-and-engineering"
    }
  ]
}
```
