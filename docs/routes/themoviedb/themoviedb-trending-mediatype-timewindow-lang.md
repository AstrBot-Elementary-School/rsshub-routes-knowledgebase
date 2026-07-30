# The Movie Database - Trending

## Coverage
`index-only`

## Route
- Namespace: `themoviedb`
- Namespace Name: `The Movie Database`
- Route Path: `/themoviedb/trending/:mediaType/:timeWindow/:lang?`
- Route Name: `Trending`
- Example: `/themoviedb/trending/tv/day/en-US`
- URL: `themoviedb.org`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `x2cf`
- Source Location: `trending.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `mediaType`: `movie` or `tv`
- `timeWindow`: `day` or `week`
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
  "example": "/themoviedb/trending/tv/day/en-US",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 101,
  "location": "trending.ts",
  "maintainers": [
    "x2cf"
  ],
  "name": "Trending",
  "parameters": {
    "lang": "Language",
    "mediaType": "`movie` or `tv`",
    "timeWindow": "`day` or `week`"
  },
  "path": "/trending/:mediaType/:timeWindow/:lang?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 399344281670 to be less than 311040000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:62:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Popular Movies — TMDB - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "65993509634566151",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.themoviedb.org/movie",
      "title": "Popular Movies — TMDB",
      "type": "feed",
      "url": "rsshub://themoviedb/trending/movie/week/feed"
    },
    {
      "description": "Popular TV Shows — TMDB - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "70777567210160141",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.themoviedb.org/tv",
      "title": "Popular TV Shows — TMDB",
      "type": "feed",
      "url": "rsshub://themoviedb/trending/tv/day/en-US"
    }
  ]
}
```
