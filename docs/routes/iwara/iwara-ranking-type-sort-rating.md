# iwara - Ranking

## Coverage
`index-only`

## Route
- Namespace: `iwara`
- Namespace Name: `iwara`
- Route Path: `/iwara/ranking/:type?/:sort?/:rating?`
- Route Name: `Ranking`
- Example: `/iwara/ranking/video/date/ecchi`
- URL: `www.iwara.tv`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `CaoMeiYouRen233`
- Source Location: `ranking.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: Content type, can be video or image, default is video
- `sort`: Sort type, can be date, trending, popularity, views, likes, default is date
- `rating`: Rating, can be all, general, ecchi, default is ecchi


## Features
- `requirePuppeteer`: true
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `www.iwara.tv/videos`
  - `www.iwara.tv/images`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/iwara/ranking/video/date/ecchi",
  "features": {
    "nsfw": true,
    "requirePuppeteer": true
  },
  "heat": 0,
  "location": "ranking.ts",
  "maintainers": [
    "CaoMeiYouRen233"
  ],
  "name": "Ranking",
  "parameters": {
    "rating": "Rating, can be all, general, ecchi, default is ecchi",
    "sort": "Sort type, can be date, trending, popularity, views, likes, default is date",
    "type": "Content type, can be video or image, default is video"
  },
  "path": "/ranking/:type?/:sort?/:rating?",
  "radar": [
    {
      "source": [
        "www.iwara.tv/videos",
        "www.iwara.tv/images"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
