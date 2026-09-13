# Uniqlo - New Arrivals

## Coverage
`index-only`

## Route
- Namespace: `uniqlo`
- Namespace Name: `Uniqlo`
- Route Path: `/uniqlo/new/:country/:category`
- Route Name: `New Arrivals`
- Example: `/uniqlo/new/sg/men`
- URL: `www.uniqlo.com`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `DIYgod`
- Source Location: `new.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `country`: currently only supports sg, us, jp
- `category`: supports `men` `women`, `kids`, `baby`


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
    "shopping"
  ],
  "example": "/uniqlo/new/sg/men",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 41,
  "location": "new.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "New Arrivals",
  "parameters": {
    "category": "supports `men` `women`, `kids`, `baby`",
    "country": "currently only supports sg, us, jp"
  },
  "path": "/new/:country/:category",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Uniqlo men new arrivals in sg - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41147805268337675",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.uniqlo.com/sg/en/feature/new/men/",
      "title": "Uniqlo men new arrivals in sg",
      "type": "feed",
      "url": "rsshub://uniqlo/new/sg/men"
    },
    {
      "description": "Uniqlo men new arrivals in us - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "164380886195041280",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.uniqlo.com/us/en/feature/new/men/",
      "title": "Uniqlo men new arrivals in us",
      "type": "feed",
      "url": "rsshub://uniqlo/new/us/men"
    }
  ]
}
```
