# UPS - Tracking

## Coverage
`index-only`

## Route
- Namespace: `ups`
- Namespace Name: `UPS`
- Route Path: `/ups/track/:trackingNumber`
- Route Name: `Tracking`
- Example: `/ups/track/1Z78R6790470567520`
- URL: `ups.com`
- Language: `_None_`
- Categories: `other`
- Maintainers: `Aquabet`
- Source Location: `track.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `trackingNumber`: The UPS tracking number (e.g., 1Z78R6790470567520).


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
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
    "other"
  ],
  "example": "/ups/track/1Z78R6790470567520",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "track.ts",
  "maintainers": [
    "Aquabet"
  ],
  "name": "Tracking",
  "parameters": {
    "trackingNumber": "The UPS tracking number (e.g., 1Z78R6790470567520)."
  },
  "path": "/track/:trackingNumber",
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
