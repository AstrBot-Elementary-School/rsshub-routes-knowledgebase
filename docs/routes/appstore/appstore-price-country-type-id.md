# App Store/Mac App Store - Price Drop

## Coverage
`index-only`

## Route
- Namespace: `appstore`
- Namespace Name: `App Store/Mac App Store`
- Route Path: `/appstore/price/:country/:type/:id`
- Route Name: `Price Drop`
- Example: `/appstore/price/us/mac/id1152443474`
- URL: `apps.apple.com/`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `HenryQW`
- Source Location: `price.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `country`: App Store Country, obtain from the app URL https://apps.apple.com/us/app/id1152443474, in this case, `us`
- `type`: App type，either `iOS` or `mac`
- `id`: App Store app id, obtain from the app URL https://apps.apple.com/us/app/id1152443474, in this case, `id1152443474`


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
  - `apps.apple.com/`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/appstore/price/us/mac/id1152443474",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 25,
  "location": "price.ts",
  "maintainers": [
    "HenryQW"
  ],
  "name": "Price Drop",
  "parameters": {
    "country": "App Store Country, obtain from the app URL https://apps.apple.com/us/app/id1152443474, in this case, `us`",
    "id": "App Store app id, obtain from the app URL https://apps.apple.com/us/app/id1152443474, in this case, `id1152443474`",
    "type": "App type，either `iOS` or `mac`"
  },
  "path": "/price/:country/:type/:id",
  "radar": [
    {
      "source": [
        "apps.apple.com/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Price watcher: Procreate Dreams for iOS - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "120423661323680768",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://apps.apple.com/us/app/id1595520602",
      "title": "Price watcher: Procreate Dreams for iOS",
      "type": "feed",
      "url": "rsshub://appstore/price/us/iOS/id1595520602"
    },
    {
      "description": "限免提醒: Squash — Web Image Compression for macOS - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "61630586048599162",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://apps.apple.com/cn/app/id1152443474",
      "title": "限免提醒: Squash — Web Image Compression for macOS",
      "type": "feed",
      "url": "rsshub://appstore/price/cn/mac/id1152443474"
    }
  ],
  "url": "apps.apple.com/"
}
```
