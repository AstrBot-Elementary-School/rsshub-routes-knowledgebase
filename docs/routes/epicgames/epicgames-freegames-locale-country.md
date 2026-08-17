# Epic Games Store - Free games

## Coverage
`index-only`

## Route
- Namespace: `epicgames`
- Namespace Name: `Epic Games Store`
- Route Path: `/epicgames/freegames/:locale?/:country?`
- Route Name: `Free games`
- Example: `/epicgames/freegames/en-US/US`
- URL: `store.epicgames.com`
- Language: `_None_`
- Categories: `game, popular`
- Maintainers: `DIYgod, NeverBehave, Zyx-A, junfengP, nczitzk, KotaHv`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `locale`: {"default": "en-US", "description": "Locale"}
- `country`: {"default": "US", "description": "Country"}


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
  - `store.epicgames.com/:locale/free-games`
- `target`: `/freegames/:locale`

## Raw JSON
```json
{
  "categories": [
    "game",
    "popular"
  ],
  "example": "/epicgames/freegames/en-US/US",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 44391,
  "location": "index.tsx",
  "maintainers": [
    "DIYgod",
    "NeverBehave",
    "Zyx-A",
    "junfengP",
    "nczitzk",
    "KotaHv"
  ],
  "name": "Free games",
  "parameters": {
    "country": {
      "default": "US",
      "description": "Country"
    },
    "locale": {
      "default": "en-US",
      "description": "Locale"
    }
  },
  "path": "/freegames/:locale?/:country?",
  "radar": [
    {
      "source": [
        "store.epicgames.com/:locale/free-games"
      ],
      "target": "/freegames/:locale"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Epic Games Store - Free Games - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41503779521380352",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://store.epicgames.com/en-US/free-games?lang=en-US",
      "title": "Epic Games Store - Free Games",
      "type": "feed",
      "url": "rsshub://epicgames/freegames/en-US/US"
    },
    {
      "description": "Epic Games Store - Free Games - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "43374760408291328",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://store.epicgames.com/zh-CN/free-games?lang=zh-CN",
      "title": "Epic Games Store - Free Games",
      "type": "feed",
      "url": "rsshub://epicgames/freegames/zh-CN/CN"
    }
  ],
  "view": 5
}
```
