# Nature Journal - Nature News

## Coverage
`index-only`

## Route
- Namespace: `nature`
- Namespace Name: `Nature Journal`
- Route Path: `/nature/news`
- Route Name: `Nature News`
- Example: `/nature/news`
- URL: `nature.com/latest-news`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `y9c, TonyRL`
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
- `supportScihub`: true

## Radar
### Rule 1
- `source`:
  - `nature.com/latest-news`
  - `nature.com/news`
  - `nature.com/`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "example": "/nature/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": true
  },
  "heat": 313,
  "location": "news.ts",
  "maintainers": [
    "y9c",
    "TonyRL"
  ],
  "name": "Nature News",
  "parameters": {},
  "path": "/news",
  "radar": [
    {
      "source": [
        "nature.com/latest-news",
        "nature.com/news",
        "nature.com/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Browse the latest news from the world's leading research journal. - Powered by RSSHub",
      "errorAt": "2026-10-01T14:50:45.177Z",
      "errorMessage": "Unexpected end of JSON input\n",
      "id": "79390521827702784",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.nature.com/latest-news",
      "title": "Nature | Latest News",
      "type": "feed",
      "url": "rsshub://nature/news"
    }
  ],
  "url": "nature.com/latest-news"
}
```
