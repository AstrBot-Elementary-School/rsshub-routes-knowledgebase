# 4KUP - Popular

## Coverage
`index-only`

## Route
- Namespace: `4kup`
- Namespace Name: `4KUP`
- Route Path: `/4kup/popular/:period`
- Route Name: `Popular`
- Example: `/4kup/popular/7`
- URL: `4kup.net/`
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
  - `4kup.net/:period`
- `target`: `/popular/:period`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/4kup/popular/7",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 331,
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
        "4kup.net/:period"
      ],
      "target": "/popular/:period"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "4KUP - Top views in 7 days - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "109193802480859136",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://4kup.net/hot-of-week/",
      "title": "4KUP - Top views in 7 days",
      "type": "feed",
      "url": "rsshub://4kup/popular/7"
    },
    {
      "description": "4KUP - Top views in 30 days - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "129386871833229312",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://4kup.net/hot-of-month/",
      "title": "4KUP - Top views in 30 days",
      "type": "feed",
      "url": "rsshub://4kup/popular/30"
    }
  ],
  "url": "4kup.net/"
}
```
