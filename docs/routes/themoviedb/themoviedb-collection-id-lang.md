# The Movie Database - Collection

## Coverage
`index-only`

## Route
- Namespace: `themoviedb`
- Namespace Name: `The Movie Database`
- Route Path: `/themoviedb/collection/:id/:lang?`
- Route Name: `Collection`
- Example: `/themoviedb/collection/131292/en-US`
- URL: `themoviedb.org`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `x2cf`
- Source Location: `collection.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: Collection ID
- `lang`: Language


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
    "multimedia"
  ],
  "example": "/themoviedb/collection/131292/en-US",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "collection.ts",
  "maintainers": [
    "x2cf"
  ],
  "name": "Collection",
  "parameters": {
    "id": "Collection ID",
    "lang": "Language"
  },
  "path": "/collection/:id/:lang?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 418871092791 to be less than 311040000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:62:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "A superhero film series based on the Marvel Comics character of the same name and part of the Marvel Cinematic Universe (MCU) series. Tony Stark AKA Iron Man, an industrialist and master engineer uses a powered exoskeleton to fight foes, with the aid of his personal assistant and love interest Pepper Potts. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "88876445004923911",
      "image": "https://image.tmdb.org/t/p/original/fbeJ7f0aD4A112Bc1tnpzyn82xO.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.themoviedb.org/collection/131292",
      "title": "Iron Man Collection — TMDB",
      "type": "feed",
      "url": "rsshub://themoviedb/collection/131292/en-US"
    }
  ]
}
```
