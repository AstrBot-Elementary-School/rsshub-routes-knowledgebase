# mymusic5 (MyMusicSheet) - User Sheets

## Coverage
`index-only`

## Route
- Namespace: `mymusicsheet`
- Namespace Name: `mymusic5 (MyMusicSheet)`
- Route Path: `/mymusicsheet/user/sheets/:username/:iso?/:freeOnly?`
- Route Name: `User Sheets`
- Example: `/mymusicsheet/user/sheets/HalcyonMusic/USD/1`
- URL: `mymusicfive.com`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `Freddd13`
- Source Location: `usersheets.tsx`
- Source Module: `_None_`

## Description
Please refer to [Wikipedia](https://en.wikipedia.org/wiki/ISO_4217#Active_codes) for ISO 4217.

## Parameters
- `username`: Username, can be found in the URL
- `iso`: ISO 4217 currency code for displaying prices, defaults to `USD`
- `freeOnly`: Only return free scores, any value to enable


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
  - `mymusicfive.com/:username/*`
  - `mymusicfive.com/:username`
- `target`: `/user/sheets/:username`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "description": "Please refer to [Wikipedia](https://en.wikipedia.org/wiki/ISO_4217#Active_codes) for ISO 4217.",
  "example": "/mymusicsheet/user/sheets/HalcyonMusic/USD/1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "usersheets.tsx",
  "maintainers": [
    "Freddd13"
  ],
  "name": "User Sheets",
  "parameters": {
    "freeOnly": "Only return free scores, any value to enable",
    "iso": "ISO 4217 currency code for displaying prices, defaults to `USD`",
    "username": "Username, can be found in the URL"
  },
  "path": "/user/sheets/:username/:iso?/:freeOnly?",
  "radar": [
    {
      "source": [
        "mymusicfive.com/:username/*",
        "mymusicfive.com/:username"
      ],
      "target": "/user/sheets/:username"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Official sheet music by HalcyonMusic (ハルシオン). Purchase Piano,Piano 61keys sheet music from HalcyonMusic (ハルシオン). 278 sheet music, I beg you, Fu Re N Do Shi Ta i, MyGO!!!!! and many others are on sale. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "1197719687631077376",
      "image": "https://img.musicfive.com/dynamic/o_jC7XEDyZfIi2f7CvzGnA/XM5ktOLyczumyqPz1lDTsWyylyLDEVRs4-mnoOCi50ZI-SS-lO-srMxHE3LGB4CsvIEDfhfna4LbeEXmGWKU_WCwk2YFEbfCgADIFulOqvP10m04OErzsjVOvpXs92fP0wPX5Y6tOS1pLokHD6akqc2oRVyy7cQRtQqgBMNVkKojure9ZhaIVODRQHd89MJH4Z4htYN26caeYLZbYM9zzAAfLrSaH5zsn0gm.auto",
      "ownerUserId": null,
      "siteUrl": "https://www.mymusicfive.com/HalcyonMusic?viewType=sheet&orderBy=createdAt",
      "title": "HalcyonMusic (ハルシオン) Official",
      "type": "feed",
      "url": "rsshub://mymusicsheet/user/sheets/HalcyonMusic/USD"
    }
  ]
}
```
