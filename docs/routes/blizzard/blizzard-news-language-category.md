# Blizzard - News

## Coverage
`index-only`

## Route
- Namespace: `blizzard`
- Namespace Name: `Blizzard`
- Route Path: `/blizzard/news/:language?/:category?`
- Route Name: `News`
- Example: `/blizzard/news`
- URL: `news.blizzard.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `nczitzk`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
Categories

| Category               | Slug                |
| ---------------------- | ------------------- |
| All News               |                     |
| Diablo II: Resurrected | diablo2             |
| Diablo III             | diablo3             |
| Diablo IV              | diablo4             |
| Diablo Immortal        | diablo-immortal     |
| Hearthstone            | hearthstone         |
| Heroes of the Storm    | heroes-of-the-storm |
| Overwatch 2            | overwatch           |
| StarCraft: Remastered  | starcraft           |
| StarCraft II           | starcraft2          |
| World of Warcraft      | world-of-warcraft   |
| Warcraft 3: Reforged   | warcraft3           |
| Warcraft Rumble        | warcraft-rumble     |
| Battle.net             | battlenet           |
| BlizzCon               | blizzcon            |
| Inside Blizzard        | blizzard            |

Language codes

| Language           | Code  |
| ------------------ | ----- |
| Deutsch            | de-de |
| English (US)       | en-us |
| English (EU)       | en-gb |
| Español (EU)       | es-es |
| Español (Latino)   | es-mx |
| Français           | fr-fr |
| Italiano           | it-it |
| Português (Brasil) | pt-br |
| Polski             | pl-pl |
| Русский            | ru-ru |
| 한국어             | ko-kr |
| ภาษาไทย            | th-th |
| 日本語             | ja-jp |
| 繁體中文           | zh-tw |

## Parameters
- `language`: Language code, see below, en-US by default
- `category`: Category, see below, All News by default


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
    "game"
  ],
  "description": "Categories\n\n| Category               | Slug                |\n| ---------------------- | ------------------- |\n| All News               |                     |\n| Diablo II: Resurrected | diablo2             |\n| Diablo III             | diablo3             |\n| Diablo IV              | diablo4             |\n| Diablo Immortal        | diablo-immortal     |\n| Hearthstone            | hearthstone         |\n| Heroes of the Storm    | heroes-of-the-storm |\n| Overwatch 2            | overwatch           |\n| StarCraft: Remastered  | starcraft           |\n| StarCraft II           | starcraft2          |\n| World of Warcraft      | world-of-warcraft   |\n| Warcraft 3: Reforged   | warcraft3           |\n| Warcraft Rumble        | warcraft-rumble     |\n| Battle.net             | battlenet           |\n| BlizzCon               | blizzcon            |\n| Inside Blizzard        | blizzard            |\n\nLanguage codes\n\n| Language           | Code  |\n| ------------------ | ----- |\n| Deutsch            | de-de |\n| English (US)       | en-us |\n| English (EU)       | en-gb |\n| Español (EU)       | es-es |\n| Español (Latino)   | es-mx |\n| Français           | fr-fr |\n| Italiano           | it-it |\n| Português (Brasil) | pt-br |\n| Polski             | pl-pl |\n| Русский            | ru-ru |\n| 한국어             | ko-kr |\n| ภาษาไทย            | th-th |\n| 日本語             | ja-jp |\n| 繁體中文           | zh-tw |",
  "example": "/blizzard/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 34,
  "location": "news.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "News",
  "parameters": {
    "category": "Category, see below, All News by default",
    "language": "Language code, see below, en-US by default"
  },
  "path": "/news/:language?/:category?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "All News - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "68902633808272384",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://news.blizzard.com/en-us",
      "title": "All News",
      "type": "feed",
      "url": "rsshub://blizzard/news"
    },
    {
      "description": "Overwatch - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "77926976521555968",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://news.blizzard.com/en-US/?filter=overwatch",
      "title": "Overwatch",
      "type": "feed",
      "url": "rsshub://blizzard/news/en-US/overwatch"
    }
  ]
}
```
