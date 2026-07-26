# DBLP - Keyword Search

## Coverage
`index-only`

## Route
- Namespace: `dblp`
- Namespace Name: `DBLP`
- Route Path: `/dblp/:field`
- Route Name: `Keyword Search`
- Example: `/dblp/knowledge%20tracing`
- URL: `dblp.org`
- Language: `_None_`
- Categories: `study`
- Maintainers: `ytno1`
- Source Location: `publication.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `field`: Research field


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
  - `dblp.org/:field`

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "example": "/dblp/knowledge%20tracing",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 7,
  "location": "publication.ts",
  "maintainers": [
    "ytno1"
  ],
  "name": "Keyword Search",
  "parameters": {
    "field": "Research field"
  },
  "path": "/:field",
  "radar": [
    {
      "source": [
        "dblp.org/:field"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "DBLP knowledge tracing RSS - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "83442921920404480",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://dblp.org/search?q=knowledge%20tracing",
      "title": "【dblp】knowledge tracing",
      "type": "feed",
      "url": "rsshub://dblp/knowledge%20tracing"
    },
    {
      "description": "DBLP software testing RSS - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "84441761514554368",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://dblp.org/search?q=software%20testing",
      "title": "【dblp】software testing",
      "type": "feed",
      "url": "rsshub://dblp/software%20testing"
    }
  ]
}
```
