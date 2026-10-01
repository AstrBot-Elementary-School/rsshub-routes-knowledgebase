# Steam - News

## Coverage
`index-only`

## Route
- Namespace: `steam`
- Namespace Name: `Steam`
- Route Path: `/steam/news/:appid/:language?`
- Route Name: `News`
- Example: `/steam/news/958260/english`
- URL: `steamcommunity.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `keocheung`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
<details>
<summary>More languages</summary>

| 语言代码                                          | 语言名称   |
| ------------------------------------------------- | ---------- |
| English                                           | english    |
| Español - España (Spanish - Spain)                | spanish    |
| Français (French)                                 | french     |
| Italiano (Italian)                                | italian    |
| Deutsch (German)                                  | german     |
| Ελληνικά (Greek)                                  | greek      |
| 한국어 (Korean)                                   | koreana    |
| 简体中文 (Simplified Chinese)                     | schinese   |
| 繁體中文 (Traditional Chinese)                    | tchinese   |
| Русский (Russian)                                 | russian    |
| ไทย (Thai)                                        | thai       |
| 日本語 (Japanese)                                 | japanese   |
| Português (Portuguese)                            | portuguese |
| Português - Brasil (Portuguese - Brazil)          | brazilian  |
| Polski (Polish)                                   | polish     |
| Dansk (Danish)                                    | danish     |
| Nederlands (Dutch)                                | dutch      |
| Suomi (Finnish)                                   | finnish    |
| Norsk (Norwegian)                                 | norwegian  |
| Svenska (Swedish)                                 | swedish    |
| Čeština (Czech)                                   | czech      |
| Magyar (Hungarian)                                | hungarian  |
| Română (Romanian)                                 | romanian   |
| Български (Bulgarian)                             | bulgarian  |
| Türkçe (Turkish)                                  | turkish    |
| Українська (Ukrainian)                            | ukrainian  |
| Tiếng Việt (Vietnamese)                           | vietnamese |
| Español - Latinoamérica (Spanish - Latin America) | latam      |

</details>

## Parameters
- `appid`: Game App ID, all digits, can be found in the URL
- `language`: Language, english by default, see below for more languages


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `title`: `News`
- `source`:
  - `steamcommunity.com/app/:appid`
  - `steamcommunity.com/app/:appid/allnews`
  - `steamcommunity.com/app/:appid/announcements`
  - `steamcommunity.com/app/:appid/news`
- `target`: `/news/:appid`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "<details>\n<summary>More languages</summary>\n\n| 语言代码                                          | 语言名称   |\n| ------------------------------------------------- | ---------- |\n| English                                           | english    |\n| Español - España (Spanish - Spain)                | spanish    |\n| Français (French)                                 | french     |\n| Italiano (Italian)                                | italian    |\n| Deutsch (German)                                  | german     |\n| Ελληνικά (Greek)                                  | greek      |\n| 한국어 (Korean)                                   | koreana    |\n| 简体中文 (Simplified Chinese)                     | schinese   |\n| 繁體中文 (Traditional Chinese)                    | tchinese   |\n| Русский (Russian)                                 | russian    |\n| ไทย (Thai)                                        | thai       |\n| 日本語 (Japanese)                                 | japanese   |\n| Português (Portuguese)                            | portuguese |\n| Português - Brasil (Portuguese - Brazil)          | brazilian  |\n| Polski (Polish)                                   | polish     |\n| Dansk (Danish)                                    | danish     |\n| Nederlands (Dutch)                                | dutch      |\n| Suomi (Finnish)                                   | finnish    |\n| Norsk (Norwegian)                                 | norwegian  |\n| Svenska (Swedish)                                 | swedish    |\n| Čeština (Czech)                                   | czech      |\n| Magyar (Hungarian)                                | hungarian  |\n| Română (Romanian)                                 | romanian   |\n| Български (Bulgarian)                             | bulgarian  |\n| Türkçe (Turkish)                                  | turkish    |\n| Українська (Ukrainian)                            | ukrainian  |\n| Tiếng Việt (Vietnamese)                           | vietnamese |\n| Español - Latinoamérica (Spanish - Latin America) | latam      |\n\n</details>",
  "example": "/steam/news/958260/english",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 107,
  "location": "news.ts",
  "maintainers": [
    "keocheung"
  ],
  "name": "News",
  "parameters": {
    "appid": "Game App ID, all digits, can be found in the URL",
    "language": "Language, english by default, see below for more languages"
  },
  "path": "/news/:appid/:language?",
  "radar": [
    {
      "source": [
        "steamcommunity.com/app/:appid",
        "steamcommunity.com/app/:appid/allnews",
        "steamcommunity.com/app/:appid/announcements",
        "steamcommunity.com/app/:appid/news"
      ],
      "target": "/news/:appid",
      "title": "News"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "App 774171 News - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "149545975496265728",
      "image": "https://shared.fastly.steamstatic.com/store_item_assets/steam/apps/774171/hero_capsule.jpg",
      "ownerUserId": null,
      "siteUrl": "https://steamcommunity.com/app/774171/allnews/",
      "title": "App 774171 News",
      "type": "feed",
      "url": "rsshub://steam/news/774171/schinese"
    },
    {
      "description": "App 960170 News - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "149547667423973376",
      "image": "https://shared.fastly.steamstatic.com/store_item_assets/steam/apps/960170/hero_capsule.jpg",
      "ownerUserId": null,
      "siteUrl": "https://steamcommunity.com/app/960170/allnews/",
      "title": "App 960170 News",
      "type": "feed",
      "url": "rsshub://steam/news/960170/schinese"
    }
  ],
  "url": "steamcommunity.com"
}
```
