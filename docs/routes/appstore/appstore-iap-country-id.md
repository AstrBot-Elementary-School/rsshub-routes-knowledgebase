# App Store/Mac App Store - In-App-Purchase Price Drop Alert

## Coverage
`index-only`

## Route
- Namespace: `appstore`
- Namespace Name: `App Store/Mac App Store`
- Route Path: `/appstore/iap/:country/:id`
- Route Name: `In-App-Purchase Price Drop Alert`
- Example: `/appstore/iap/us/id953286746`
- URL: `apps.apple.com`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `HenryQW`
- Source Location: `in-app-purchase.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `country`: App Store Country, obtain from the app URL https://apps.apple.com/us/app/id953286746, in this case, `us`
- `id`: App Store app id, obtain from the app URL https://apps.apple.com/us/app/id953286746, in this case, `id953286746`


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
    "program-update"
  ],
  "example": "/appstore/iap/us/id953286746",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 5,
  "location": "in-app-purchase.ts",
  "maintainers": [
    "HenryQW"
  ],
  "name": "In-App-Purchase Price Drop Alert",
  "parameters": {
    "country": "App Store Country, obtain from the app URL https://apps.apple.com/us/app/id953286746, in this case, `us`",
    "id": "App Store app id, obtain from the app URL https://apps.apple.com/us/app/id953286746, in this case, `id953286746`"
  },
  "path": "/iap/:country/:id",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "内购限免提醒: Darkroom: Photo & Video Editor for macOS - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "145148341029475345",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://apps.apple.com/cn/app/id953286746",
      "title": "内购限免提醒: Darkroom: Photo & Video Editor for macOS",
      "type": "feed",
      "url": "rsshub://appstore/iap/cn/id953286746"
    }
  ]
}
```
