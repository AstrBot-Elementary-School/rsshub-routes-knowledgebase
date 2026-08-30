# TrendForce - News

## Coverage
`index-only`

## Route
- Namespace: `trendforce`
- Namespace Name: `TrendForce`
- Route Path: `/trendforce/news`
- Route Name: `News`
- Example: `/trendforce/news`
- URL: `www.trendforce.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `new.ts`
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
  - `www.trendforce.com/news/`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/trendforce/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 15,
  "location": "new.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "News",
  "path": "/news",
  "radar": [
    {
      "source": [
        "www.trendforce.com/news/"
      ],
      "target": "/news"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "TrendForce offers hi-tech industry research reports, including market bulletins, industry analysis and price trends, helping businesses tackle global challenges - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "186158955335655424",
      "image": "https://www.trendforce.com/images/trendforce_og_04.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.trendforce.com/news/",
      "title": "News | TrendForce",
      "type": "feed",
      "url": "rsshub://trendforce/news"
    }
  ],
  "url": "www.trendforce.com",
  "view": 0
}
```
