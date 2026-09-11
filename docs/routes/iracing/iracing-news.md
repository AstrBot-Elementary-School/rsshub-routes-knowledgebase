# iRacing - News

## Coverage
`index-only`

## Route
- Namespace: `iracing`
- Namespace Name: `iRacing`
- Route Path: `/iracing/news`
- Route Name: `News`
- Example: `/iracing/news`
- URL: `iracing.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `canonnizq`
- Source Location: `news.ts`
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
  - `www.iracing.com/category/news/sim-racing-news`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/iracing/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "canonnizq"
  ],
  "name": "News",
  "path": "/news",
  "radar": [
    {
      "source": [
        "www.iracing.com/category/news/sim-racing-news"
      ],
      "target": "/news"
    }
  ],
  "topFeeds": []
}
```
