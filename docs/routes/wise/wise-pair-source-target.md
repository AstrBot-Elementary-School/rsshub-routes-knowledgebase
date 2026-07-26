# Wise - FX Pair Yesterday

## Coverage
`index-only`

## Route
- Namespace: `wise`
- Namespace Name: `Wise`
- Route Path: `/wise/pair/:source/:target`
- Route Name: `FX Pair Yesterday`
- Example: `/wise/pair/GBP/USD`
- URL: `wise.com`
- Language: `_None_`
- Categories: `other`
- Maintainers: `HenryQW`
- Source Location: `pair.tsx`
- Source Module: `_None_`

## Description
Refer to [the list of supported currencies](https://wise.com/tools/exchange-rate-alerts/).

## Parameters
- `source`: Base currency abbreviation
- `target`: Quote currency abbreviation


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
    "other"
  ],
  "description": "Refer to [the list of supported currencies](https://wise.com/tools/exchange-rate-alerts/).",
  "example": "/wise/pair/GBP/USD",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "pair.tsx",
  "maintainers": [
    "HenryQW"
  ],
  "name": "FX Pair Yesterday",
  "parameters": {
    "source": "Base currency abbreviation",
    "target": "Quote currency abbreviation"
  },
  "path": "/pair/:source/:target",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Exchange Rate from Wise - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "61948380852672513",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://wise.com/tools/exchange-rate-alerts/",
      "title": "USD to CNY by Wise",
      "type": "feed",
      "url": "rsshub://wise/pair/USD/CNY"
    }
  ]
}
```
