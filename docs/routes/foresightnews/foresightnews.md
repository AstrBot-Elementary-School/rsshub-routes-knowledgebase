# Foresight News - 精选资讯

## Coverage
`index-only`

## Route
- Namespace: `foresightnews`
- Namespace Name: `Foresight News`
- Route Path: `/foresightnews/`
- Route Name: `精选资讯`
- Example: `/foresightnews`
- URL: `foresightnews.pro/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `foresightnews.pro/`
- `target`: ``

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/foresightnews",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "精选资讯",
  "path": "/",
  "radar": [
    {
      "source": [
        "foresightnews.pro/"
      ],
      "target": ""
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "foresightnews.pro/"
}
```
