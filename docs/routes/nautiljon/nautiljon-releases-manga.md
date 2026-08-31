# Nautiljon - France manga releases

## Coverage
`index-only`

## Route
- Namespace: `nautiljon`
- Namespace Name: `Nautiljon`
- Route Path: `/nautiljon/releases/manga`
- Route Name: `France manga releases`
- Example: `/nautiljon/releases/manga`
- URL: `nautiljon.com`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `Fafnor`
- Source Location: `manga-releases.ts`
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
  - `nautiljon.com/`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/nautiljon/releases/manga",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "manga-releases.ts",
  "maintainers": [
    "Fafnor"
  ],
  "name": "France manga releases",
  "parameters": {},
  "path": "/releases/manga",
  "radar": [
    {
      "source": [
        "nautiljon.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Nautiljon France Manga Releases - Powered by RSSHub",
      "errorAt": "2025-11-26T21:28:38.237Z",
      "errorMessage": "[GET] \"https://www.nautiljon.com/planning/manga/\": 403 Forbidden\n",
      "id": "110847445537060864",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.nautiljon.com/planning/manga/",
      "title": "Nautiljon France Manga Releases",
      "type": "feed",
      "url": "rsshub://nautiljon/releases/manga"
    }
  ],
  "url": "nautiljon.com"
}
```
