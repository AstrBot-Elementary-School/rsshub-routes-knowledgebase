# Steam - Discussion List

## Coverage
`index-only`

## Route
- Namespace: `steam`
- Namespace Name: `Steam`
- Route Path: `/steam/discussions/:appid/:feature?`
- Route Name: `Discussion List`
- Example: `/steam/discussions/730`
- URL: `steamcommunity.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `NekoAria`
- Source Location: `discussion-list.ts`
- Source Module: `_None_`

## Description
This new-topic feed enriches up to 15 topics from Steam's first, most-recently-active page with their full original posts and publication times. RSSHub sorts items by publication time by default; use `?sorted=false` to retain Steam's activity order. Recently created topics beyond that page may be missed. Pagination is not supported.

## Parameters
- `appid`: App ID, found in the Steam Community URL
- `feature`: {"default": "0", "description": "App-local discussion subforum slot, found in the Steam Community URL"}


## Features
- `requirePuppeteer`: false
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `steamcommunity.com/app/:appid/discussions`
- `target`: `/discussions/:appid`
### Rule 2
- `source`:
  - `steamcommunity.com/app/:appid/discussions/:feature`
- `target`: `/discussions/:appid/:feature`
### Rule 3
- `source`:
  - `steamcommunity.com/app/:appid/discussions/:feature/:topicId`
- `target`: `/discussions/:appid/:feature`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "This new-topic feed enriches up to 15 topics from Steam's first, most-recently-active page with their full original posts and publication times. RSSHub sorts items by publication time by default; use `?sorted=false` to retain Steam's activity order. Recently created topics beyond that page may be missed. Pagination is not supported.",
  "example": "/steam/discussions/730",
  "features": {
    "requirePuppeteer": false,
    "supportRadar": true
  },
  "heat": 0,
  "location": "discussion-list.ts",
  "maintainers": [
    "NekoAria"
  ],
  "name": "Discussion List",
  "parameters": {
    "appid": "App ID, found in the Steam Community URL",
    "feature": {
      "default": "0",
      "description": "App-local discussion subforum slot, found in the Steam Community URL"
    }
  },
  "path": "/discussions/:appid/:feature?",
  "radar": [
    {
      "source": [
        "steamcommunity.com/app/:appid/discussions"
      ],
      "target": "/discussions/:appid"
    },
    {
      "source": [
        "steamcommunity.com/app/:appid/discussions/:feature"
      ],
      "target": "/discussions/:appid/:feature"
    },
    {
      "source": [
        "steamcommunity.com/app/:appid/discussions/:feature/:topicId"
      ],
      "target": "/discussions/:appid/:feature"
    }
  ],
  "topFeeds": [],
  "url": "steamcommunity.com"
}
```
