# NASA - Astronomy Picture of the Day

## Coverage
`index-only`

## Route
- Namespace: `nasa`
- Namespace Name: `NASA`
- Route Path: `/nasa/apod`
- Route Name: `Astronomy Picture of the Day`
- Example: `/nasa/apod`
- URL: `apod.nasa.govundefined`
- Language: `_None_`
- Categories: `picture, popular`
- Maintainers: `nczitzk, williamgateszhao`
- Source Location: `apod.ts`
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
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `apod.nasa.govundefined`

## Raw JSON
```json
{
  "categories": [
    "picture",
    "popular"
  ],
  "example": "/nasa/apod",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 48366,
  "location": "apod.ts",
  "maintainers": [
    "nczitzk",
    "williamgateszhao"
  ],
  "name": "Astronomy Picture of the Day",
  "parameters": {},
  "path": "/apod",
  "radar": [
    {
      "source": [
        "apod.nasa.govundefined"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "NASA Astronomy Picture of the Day - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41356263889737728",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://apod.nasa.gov/apod/archivepix.html",
      "title": "NASA Astronomy Picture of the Day",
      "type": "feed",
      "url": "rsshub://nasa/apod"
    }
  ],
  "url": "apod.nasa.govundefined",
  "view": 2
}
```
