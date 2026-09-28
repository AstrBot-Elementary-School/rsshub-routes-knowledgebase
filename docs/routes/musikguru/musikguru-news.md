# MusikGuru - News

## Coverage
`index-only`

## Route
- Namespace: `musikguru`
- Namespace Name: `MusikGuru`
- Route Path: `/musikguru/news`
- Route Name: `News`
- Example: `/musikguru/news`
- URL: `musikguru.de`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `nczitzk`
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
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `musikguru.de/news`
- `target`: `news`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/musikguru/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "News",
  "path": "/news",
  "radar": [
    {
      "source": [
        "musikguru.de/news"
      ],
      "target": "news"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "musikguru.de",
  "view": 0
}
```
