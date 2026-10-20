# NASA - Astronomy Picture of the Day

## Coverage
`index-only`

## Route
- Namespace: `nasa`
- Namespace Name: `NASA`
- Route Path: `/nasa/apod`
- Route Name: `Astronomy Picture of the Day`
- Example: `/nasa/apod`
- URL: `apod.nasa.gov/apod/`
- Language: `_None_`
- Categories: `picture, popular`
- Maintainers: `nczitzk, williamgateszhao`
- Source Location: `apod.ts`
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
  - `apod.nasa.gov/apod/*path`
  - `apod.nasa.gov/apod`
### Rule 2
- `source`:
  - `science.nasa.gov/apod/*path`
  - `science.nasa.gov/apod`

## Raw JSON
```json
{
  "categories": [
    "picture",
    "popular"
  ],
  "example": "/nasa/apod",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 60915,
  "location": "apod.ts",
  "maintainers": [
    "nczitzk",
    "williamgateszhao"
  ],
  "name": "Astronomy Picture of the Day",
  "parameters": {},
  "path": "/apod",
  "radar": [
    {
      "source": [
        "apod.nasa.gov/apod/*path",
        "apod.nasa.gov/apod"
      ]
    },
    {
      "source": [
        "science.nasa.gov/apod/*path",
        "science.nasa.gov/apod"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "NASA Astronomy Picture of the Day - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41356263889737728",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://science.nasa.gov/apod/archive/",
      "title": "NASA Astronomy Picture of the Day",
      "type": "feed",
      "url": "rsshub://nasa/apod"
    }
  ],
  "url": "apod.nasa.gov/apod/",
  "view": 2
}
```
