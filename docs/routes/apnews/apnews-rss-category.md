# AP News - News

## Coverage
`index-only`

## Route
- Namespace: `apnews`
- Namespace Name: `AP News`
- Route Path: `/apnews/rss/:category?`
- Route Name: `News`
- Example: `/apnews/rss/business`
- URL: `apnews.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `zoenglinghou, mjysci, TonyRL`
- Source Location: `rss.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: {"default": "index", "description": "Category from the first segment of the corresponding site, or `index` for the front page."}


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
  - `apnews.com/:category`
- `target`: `/rss/:category`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/apnews/rss/business",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "rss.ts",
  "maintainers": [
    "zoenglinghou",
    "mjysci",
    "TonyRL"
  ],
  "name": "News",
  "parameters": {
    "category": {
      "default": "index",
      "description": "Category from the first segment of the corresponding site, or `index` for the front page."
    }
  },
  "path": "/rss/:category?",
  "radar": [
    {
      "source": [
        "apnews.com/:category"
      ],
      "target": "/rss/:category"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [],
  "view": 0
}
```
