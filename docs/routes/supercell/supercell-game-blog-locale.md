# Supercell - Game Blog

## Coverage
`index-only`

## Route
- Namespace: `supercell`
- Namespace Name: `Supercell`
- Route Path: `/supercell/:game/blog/:locale?`
- Route Name: `Game Blog`
- Example: `/supercell/clashroyale/blog/zh`
- URL: `supercell.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `fishyo`
- Source Location: `blog.ts`
- Source Module: `_None_`

## Description
Supported games

| Game           | Slug         |
| -------------- | ------------ |
| Clash Royale   | clashroyale  |
| Brawl Stars    | brawlstars   |
| Clash of Clans | clashofclans |
| Boom Beach     | boombeach    |
| Hay Day        | hayday       |

Language codes

| Language  | Code    |
| --------- | ------- |
| English   |         |
| 繁體中文  | zh      |
| 简体中文  | zh-hans |
| Français  | fr      |
| Deutsch   | de      |
| Indonesia | id      |
| Italiano  | it      |
| 日本語    | ja      |
| 한국어    | ko      |
| Português | pt      |
| Русский   | ru      |
| Español   | es      |

## Parameters
- `game`: Game name, see below
- `locale`: Language code, see below, English by default


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
  - `supercell.com/en/games/:game/:locale/blog`
  - `supercell.com/en/games/:game/blog`
- `target`: `/:game/blog/:locale?`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "Supported games\n\n| Game           | Slug         |\n| -------------- | ------------ |\n| Clash Royale   | clashroyale  |\n| Brawl Stars    | brawlstars   |\n| Clash of Clans | clashofclans |\n| Boom Beach     | boombeach    |\n| Hay Day        | hayday       |\n\nLanguage codes\n\n| Language  | Code    |\n| --------- | ------- |\n| English   |         |\n| 繁體中文  | zh      |\n| 简体中文  | zh-hans |\n| Français  | fr      |\n| Deutsch   | de      |\n| Indonesia | id      |\n| Italiano  | it      |\n| 日本語    | ja      |\n| 한국어    | ko      |\n| Português | pt      |\n| Русский   | ru      |\n| Español   | es      |",
  "example": "/supercell/clashroyale/blog/zh",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "blog.ts",
  "maintainers": [
    "fishyo"
  ],
  "name": "Game Blog",
  "parameters": {
    "game": "Game name, see below",
    "locale": "Language code, see below, English by default"
  },
  "path": "/:game/blog/:locale?",
  "radar": [
    {
      "source": [
        "supercell.com/en/games/:game/:locale/blog",
        "supercell.com/en/games/:game/blog"
      ],
      "target": "/:game/blog/:locale?"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Clash of Clans Blog - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "1189425344533102592",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://supercell.com/en/games/clashofclans/blog/",
      "title": "Clash of Clans Blog",
      "type": "feed",
      "url": "rsshub://supercell/clashofclans/blog"
    }
  ]
}
```
