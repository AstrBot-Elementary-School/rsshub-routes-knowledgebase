# Steam - Discussion Thread

## Coverage
`index-only`

## Route
- Namespace: `steam`
- Namespace Name: `Steam`
- Route Path: `/steam/discussion/:appid/:feature/:topicId`
- Route Name: `Discussion Thread`
- Example: `/steam/discussion/730/0/563667940587817948`
- URL: `steamcommunity.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `NekoAria`
- Source Location: `discussion-thread.ts`
- Source Module: `_None_`

## Description
This route contains the original post and up to 15 replies from each of the first and current last pages. Replies on intervening pages are not included, and pagination is not supported.

## Parameters
- `appid`: App ID, found in the Steam Community URL
- `feature`: App-local discussion subforum slot, found in the Steam Community URL
- `topicId`: Discussion topic ID, found in the Steam Community URL


## Features
- `requirePuppeteer`: false
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `steamcommunity.com/app/:appid/discussions/:feature/:topicId`
- `target`: `/discussion/:appid/:feature/:topicId`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "This route contains the original post and up to 15 replies from each of the first and current last pages. Replies on intervening pages are not included, and pagination is not supported.",
  "example": "/steam/discussion/730/0/563667940587817948",
  "features": {
    "requirePuppeteer": false,
    "supportRadar": true
  },
  "heat": 0,
  "location": "discussion-thread.ts",
  "maintainers": [
    "NekoAria"
  ],
  "name": "Discussion Thread",
  "parameters": {
    "appid": "App ID, found in the Steam Community URL",
    "feature": "App-local discussion subforum slot, found in the Steam Community URL",
    "topicId": "Discussion topic ID, found in the Steam Community URL"
  },
  "path": "/discussion/:appid/:feature/:topicId",
  "radar": [
    {
      "source": [
        "steamcommunity.com/app/:appid/discussions/:feature/:topicId"
      ],
      "target": "/discussion/:appid/:feature/:topicId"
    }
  ],
  "topFeeds": [],
  "url": "steamcommunity.com"
}
```
