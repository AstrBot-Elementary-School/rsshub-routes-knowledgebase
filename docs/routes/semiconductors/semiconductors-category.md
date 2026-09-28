# Semiconductor Industry Association - Latest News

## Coverage
`index-only`

## Route
- Namespace: `semiconductors`
- Namespace Name: `Semiconductor Industry Association`
- Route Path: `/semiconductors/:category{.+}?`
- Route Name: `Latest News`
- Example: `/semiconductors/news-events/latest-news`
- URL: `www.semiconductors.org`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
To subscribe to [Latest News](https://www.semiconductors.org/news-events/latest-news/), where the source URL is `https://www.semiconductors.org/news-events/latest-news/`, extract the certain parts from this URL to be used as parameters, resulting in the route as [`/semiconductors/news-events/latest-news`](https://rsshub.app/semiconductors/news-events/latest-news).
:::

## Parameters
- `category`: {"description": "Category, `news-events/latest-news` by default"}


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
  - `www.semiconductors.org/:category`
- `target`: `/:category`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\nTo subscribe to [Latest News](https://www.semiconductors.org/news-events/latest-news/), where the source URL is `https://www.semiconductors.org/news-events/latest-news/`, extract the certain parts from this URL to be used as parameters, resulting in the route as [`/semiconductors/news-events/latest-news`](https://rsshub.app/semiconductors/news-events/latest-news).\n:::",
  "example": "/semiconductors/news-events/latest-news",
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
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Latest News",
  "parameters": {
    "category": {
      "description": "Category, `news-events/latest-news` by default"
    }
  },
  "path": "/:category{.+}?",
  "radar": [
    {
      "source": [
        "www.semiconductors.org/:category"
      ],
      "target": "/:category"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "www.semiconductors.org",
  "view": 0
}
```
