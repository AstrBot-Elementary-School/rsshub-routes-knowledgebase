# F-Droid - App Update

## Coverage
`index-only`

## Route
- Namespace: `f-droid`
- Namespace Name: `F-Droid`
- Route Path: `/f-droid/apprelease/:app`
- Route Name: `App Update`
- Example: `/f-droid/apprelease/com.termux`
- URL: `f-droid.org`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `garywill`
- Source Location: `apprelease.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `app`: App's package name


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
  - `f-droid.org/en/packages/:app/`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/f-droid/apprelease/com.termux",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 13,
  "location": "apprelease.ts",
  "maintainers": [
    "garywill"
  ],
  "name": "App Update",
  "parameters": {
    "app": "App's package name"
  },
  "path": "/apprelease/:app",
  "radar": [
    {
      "source": [
        "f-droid.org/en/packages/:app/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Termux releases on F-Droid - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59812950247047168",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://f-droid.org/en/packages/com.termux/",
      "title": "Termux releases on F-Droid",
      "type": "feed",
      "url": "rsshub://f-droid/apprelease/com.termux"
    }
  ]
}
```
