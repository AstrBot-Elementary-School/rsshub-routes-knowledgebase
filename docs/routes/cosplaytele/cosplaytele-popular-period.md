# CosplayTele - Popular

## Coverage
`index-only`

## Route
- Namespace: `cosplaytele`
- Namespace Name: `CosplayTele`
- Route Path: `/cosplaytele/popular/:period`
- Route Name: `Popular`
- Example: `/cosplaytele/popular/3`
- URL: `cosplaytele.com/`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `AiraNadih`
- Source Location: `popular.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `period`: Days


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
  - `cosplaytele.com/:period`
- `target`: `/popular/:period`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/cosplaytele/popular/3",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 380,
  "location": "popular.ts",
  "maintainers": [
    "AiraNadih"
  ],
  "name": "Popular",
  "parameters": {
    "period": "Days"
  },
  "path": "/popular/:period",
  "radar": [
    {
      "source": [
        "cosplaytele.com/:period"
      ],
      "target": "/popular/:period"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "CosplayTele - Top views in 30 days - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "107079632432448512",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://cosplaytele.com/30-day/",
      "title": "CosplayTele - Top views in 30 days",
      "type": "feed",
      "url": "rsshub://cosplaytele/popular/30"
    },
    {
      "description": "CosplayTele - Top views in 3 days - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "108033837965102080",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://cosplaytele.com/3-day/",
      "title": "CosplayTele - Top views in 3 days",
      "type": "feed",
      "url": "rsshub://cosplaytele/popular/3"
    }
  ],
  "url": "cosplaytele.com/"
}
```
