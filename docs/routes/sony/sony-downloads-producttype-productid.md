# Sony - Software Downloads

## Coverage
`index-only`

## Route
- Namespace: `sony`
- Namespace Name: `Sony`
- Route Path: `/sony/downloads/:productType/:productId`
- Route Name: `Software Downloads`
- Example: `/sony/downloads/product/nw-wm1am2`
- URL: `sony.com`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `IvanWng97`
- Source Location: `downloads.ts`
- Source Module: `_None_`

## Description
::: tip
Open `https://www.sony.com/electronics/support` and search for the corresponding product, such as `Sony A7M4`, the website corresponding to which is `https://www.sony.com/electronics/support/e-mount-body-ilce-7-series/ilce-7m4/downloads`, where `productType` is `e-mount-body-ilce-7-series` and `productId` is `ilce-7m4`.
:::

## Parameters
- `productType`: product type
- `productId`: product id


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
  - `sony.com/electronics/support/:productType/:productId/downloads`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "description": "::: tip\nOpen `https://www.sony.com/electronics/support` and search for the corresponding product, such as `Sony A7M4`, the website corresponding to which is `https://www.sony.com/electronics/support/e-mount-body-ilce-7-series/ilce-7m4/downloads`, where `productType` is `e-mount-body-ilce-7-series` and `productId` is `ilce-7m4`.\n:::",
  "example": "/sony/downloads/product/nw-wm1am2",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "downloads.ts",
  "maintainers": [
    "IvanWng97"
  ],
  "name": "Software Downloads",
  "parameters": {
    "productId": "product id",
    "productType": "product type"
  },
  "path": "/downloads/:productType/:productId",
  "radar": [
    {
      "source": [
        "sony.com/electronics/support/:productType/:productId/downloads"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
