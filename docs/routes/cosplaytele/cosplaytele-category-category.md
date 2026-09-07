# CosplayTele - Category

## Coverage
`index-only`

## Route
- Namespace: `cosplaytele`
- Namespace Name: `CosplayTele`
- Route Path: `/cosplaytele/category/:category`
- Route Name: `Category`
- Example: `/cosplaytele/category/cosplay`
- URL: `cosplaytele.com/`
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
  - `cosplaytele.com/category/:category`
- `target`: `/category/:category`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/cosplaytele/category/cosplay",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 321,
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
        "cosplaytele.com/category/:category"
      ],
      "target": "/category/:category"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "CosplayTele - Category: cosplay - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "107241997543607296",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://cosplaytele.com/category/cosplay/",
      "title": "CosplayTele - Category: cosplay",
      "type": "feed",
      "url": "rsshub://cosplaytele/category/cosplay"
    },
    {
      "description": "CosplayTele - Category: yuuhui - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "121742107387352065",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://cosplaytele.com/category/yuuhui/",
      "title": "CosplayTele - Category: yuuhui",
      "type": "feed",
      "url": "rsshub://cosplaytele/category/yuuhui"
    }
  ],
  "url": "cosplaytele.com/"
}
```
