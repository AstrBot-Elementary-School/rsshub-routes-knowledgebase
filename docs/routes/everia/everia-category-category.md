# EVERIA.CLUB - Images with category

## Coverage
`index-only`

## Route
- Namespace: `everia`
- Namespace Name: `EVERIA.CLUB`
- Route Path: `/everia/category/:category`
- Route Name: `Images with category`
- Example: `/everia/category/cosplay`
- URL: `everia.club`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `KTachibanaM, AiraNadih`
- Source Location: `category.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: Category of the image stream


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
  - `everia.club/category/:category`
- `target`: `/category/:category`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/everia/category/cosplay",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 155,
  "location": "category.ts",
  "maintainers": [
    "KTachibanaM",
    "AiraNadih"
  ],
  "name": "Images with category",
  "parameters": {
    "category": "Category of the image stream"
  },
  "path": "/category/:category",
  "radar": [
    {
      "source": [
        "everia.club/category/:category"
      ],
      "target": "/category/:category"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "EVERIA.CLUB - Category: chinese - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "160206686101994527",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://everia.club/category/chinese/",
      "title": "EVERIA.CLUB - Category: chinese",
      "type": "feed",
      "url": "rsshub://everia/category/chinese"
    },
    {
      "description": "EVERIA.CLUB - Category: korea - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "160206686101994524",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://everia.club/category/korea/",
      "title": "EVERIA.CLUB - Category: korea",
      "type": "feed",
      "url": "rsshub://everia/category/korea"
    }
  ]
}
```
