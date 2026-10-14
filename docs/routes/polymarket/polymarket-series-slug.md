# Polymarket - Series

## Coverage
`index-only`

## Route
- Namespace: `polymarket`
- Namespace Name: `Polymarket`
- Route Path: `/polymarket/series/:slug?`
- Route Name: `Series`
- Example: `/polymarket/series`
- URL: `polymarket.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `heqi201255`
- Source Location: `series.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `slug`: {"description": "Series slug, e.g. nfl, nba, mlb. If omitted, lists all series."}


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
  - `polymarket.com/series/:slug`
- `target`: `/series/:slug`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/polymarket/series",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "series.ts",
  "maintainers": [
    "heqi201255"
  ],
  "name": "Series",
  "parameters": {
    "slug": {
      "description": "Series slug, e.g. nfl, nba, mlb. If omitted, lists all series."
    }
  },
  "path": "/series/:slug?",
  "radar": [
    {
      "source": [
        "polymarket.com/series/:slug"
      ],
      "target": "/series/:slug"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "polymarket.com"
}
```
