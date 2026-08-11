# 4KHD - Category

## Coverage
`index-only`

## Route
- Namespace: `4khd`
- Namespace Name: `4KHD`
- Route Path: `/4khd/category/:category`
- Route Name: `Category`
- Example: `/4khd/category/cosplay`
- URL: `www.4khd.com/`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `AiraNadih`
- Source Location: `category.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: Category


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `www.4khd.com/pages/:category`
- `target`: `/category/:category`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/4khd/category/cosplay",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 409,
  "location": "category.ts",
  "maintainers": [
    "AiraNadih"
  ],
  "name": "Category",
  "parameters": {
    "category": "Category"
  },
  "path": "/category/:category",
  "radar": [
    {
      "source": [
        "www.4khd.com/pages/:category"
      ],
      "target": "/category/:category"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "4KHD - Category: popular - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "144330669175630848",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.4khd.com/pages/popular/",
      "title": "4KHD - Category: popular",
      "type": "feed",
      "url": "rsshub://4khd/category/popular"
    },
    {
      "description": "4KHD - Category: cosplay - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "111946001442435072",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.4khd.com/pages/cosplay/",
      "title": "4KHD - Category: cosplay",
      "type": "feed",
      "url": "rsshub://4khd/category/cosplay"
    }
  ],
  "url": "www.4khd.com/"
}
```
