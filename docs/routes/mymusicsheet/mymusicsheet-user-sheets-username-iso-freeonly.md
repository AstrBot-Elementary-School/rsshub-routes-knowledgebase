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
    "code": 0
  },
  "topFeeds": []
}
```
