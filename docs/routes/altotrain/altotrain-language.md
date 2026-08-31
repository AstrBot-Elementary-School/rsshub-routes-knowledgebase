# Alto - Toronto-Québec City High-Speed Rail Network - Alto News

## Coverage
`index-only`

## Route
- Namespace: `altotrain`
- Namespace Name: `Alto - Toronto-Québec City High-Speed Rail Network`
- Route Path: `/altotrain/:language?`
- Route Name: `Alto News`
- Example: `/altotrain/en`
- URL: `altotrain.ca`
- Language: `_None_`
- Categories: `travel`
- Maintainers: `elibroftw`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `altotrain.ca/:language`
  - `altotrain.ca/:language/news`
  - `altotrain.ca/:language/nouvelles`
- `target`: `/:language`

## Raw JSON
```json
{
  "categories": [
    "travel"
  ],
  "example": "/altotrain/en",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "elibroftw"
  ],
  "name": "Alto News",
  "path": "/:language?",
  "radar": [
    {
      "source": [
        "altotrain.ca/:language",
        "altotrain.ca/:language/news",
        "altotrain.ca/:language/nouvelles"
      ],
      "target": "/:language"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
