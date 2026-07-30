# The Movie Database - Sheet

## Coverage
`index-only`

## Route
- Namespace: `themoviedb`
- Namespace Name: `The Movie Database`
- Route Path: `/themoviedb/:mediaType/:sheet/:lang?`
- Route Name: `Sheet`
- Example: `/themoviedb/tv/top-rated/en-US`
- URL: `themoviedb.org`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `x2cf`
- Source Location: `sheet.ts`
- Source Module: `_None_`

## Description
When `mediaType` is `tv`, `sheet` should be:

| Airing Today | On TV      | Top Rated |
| ------------ | ---------- | --------- |
| airing-today | on-the-air | top-rated |

When `mediaType` is `movie`, `sheet` should be:

| Now Playing | Upcoming | Top Rated |
| ----------- | -------- | --------- |
| now-playing | upcoming | top-rated |

## Parameters
- `mediaType`: `movie` or `tv`
- `sheet`: Sheet, see below
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
  "description": "When `mediaType` is `tv`, `sheet` should be:\n\n| Airing Today | On TV      | Top Rated |\n| ------------ | ---------- | --------- |\n| airing-today | on-the-air | top-rated |\n\nWhen `mediaType` is `movie`, `sheet` should be:\n\n| Now Playing | Upcoming | Top Rated |\n| ----------- | -------- | --------- |\n| now-playing | upcoming | top-rated |",
  "example": "/themoviedb/tv/top-rated/en-US",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 10,
  "location": "sheet.ts",
  "maintainers": [
    "x2cf"
  ],
  "name": "Sheet",
  "parameters": {
    "lang": "Language",
    "mediaType": "`movie` or `tv`",
    "sheet": "Sheet, see below"
  },
  "path": "/:mediaType/:sheet/:lang?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 338518681385 to be less than 311040000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:62:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Now Playing Movies — TMDB - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "80092327093291008",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.themoviedb.org/movie/now-playing",
      "title": "Now Playing Movies — TMDB",
      "type": "feed",
      "url": "rsshub://themoviedb/movie/now-playing"
    },
    {
      "description": "TV Shows Airing Today — TMDB - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "80097978467319808",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.themoviedb.org/tv/airing-today",
      "title": "TV Shows Airing Today — TMDB",
      "type": "feed",
      "url": "rsshub://themoviedb/tv/airing-today"
    }
  ]
}
```
