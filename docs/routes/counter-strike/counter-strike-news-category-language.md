# Counter Strike - News

## Coverage
`index-only`

## Route
- Namespace: `counter-strike`
- Namespace Name: `Counter Strike`
- Route Path: `/counter-strike/news/:category?/:language?`
- Route Name: `News`
- Example: `/counter-strike/news`
- URL: `www.counter-strike.net`
- Language: `_None_`
- Categories: `game`
- Maintainers: `nczitzk`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
::: tip
If you subscribe to [Updates in English](https://www.counter-strike.net/news/updates?l=english)，where the URL is `https://www.counter-strike.net/news/updates?l=english`, extract the `l`, which is `english`, and use it as the parameter to fill in. Therefore, the route will be [`/counter-strike/news/updates/english`](https://rsshub.app/counter-strike/news/updates/english).
:::

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
- `category`: Category, `updates` or `all`, `all` by default
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
- `source`:
  - `www.counter-strike.net/news`
  - `www.counter-strike.net/`
- `target`: `/news/all`
### Rule 2
- `source`:
  - `www.counter-strike.net/news/:category`
- `target`: `/news/:category`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "::: tip\nIf you subscribe to [Updates in English](https://www.counter-strike.net/news/updates?l=english)，where the URL is `https://www.counter-strike.net/news/updates?l=english`, extract the `l`, which is `english`, and use it as the parameter to fill in. Therefore, the route will be [`/counter-strike/news/updates/english`](https://rsshub.app/counter-strike/news/updates/english).\n:::\n\n<details>\n<summary>More languages</summary>\n\n| 语言代码                                          | 语言名称   |\n| ------------------------------------------------- | ---------- |\n| English                                           | english    |\n| Español - España (Spanish - Spain)                | spanish    |\n| Français (French)                                 | french     |\n| Italiano (Italian)                                | italian    |\n| Deutsch (German)                                  | german     |\n| Ελληνικά (Greek)                                  | greek      |\n| 한국어 (Korean)                                   | koreana    |\n| 简体中文 (Simplified Chinese)                     | schinese   |\n| 繁體中文 (Traditional Chinese)                    | tchinese   |\n| Русский (Russian)                                 | russian    |\n| ไทย (Thai)                                        | thai       |\n| 日本語 (Japanese)                                 | japanese   |\n| Português (Portuguese)                            | portuguese |\n| Português - Brasil (Portuguese - Brazil)          | brazilian  |\n| Polski (Polish)                                   | polish     |\n| Dansk (Danish)                                    | danish     |\n| Nederlands (Dutch)                                | dutch      |\n| Suomi (Finnish)                                   | finnish    |\n| Norsk (Norwegian)                                 | norwegian  |\n| Svenska (Swedish)                                 | swedish    |\n| Čeština (Czech)                                   | czech      |\n| Magyar (Hungarian)                                | hungarian  |\n| Română (Romanian)                                 | romanian   |\n| Български (Bulgarian)                             | bulgarian  |\n| Türkçe (Turkish)                                  | turkish    |\n| Українська (Ukrainian)                            | ukrainian  |\n| Tiếng Việt (Vietnamese)                           | vietnamese |\n| Español - Latinoamérica (Spanish - Latin America) | latam      |\n\n</details>",
  "example": "/counter-strike/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 20,
  "location": "news.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "News",
  "parameters": {
    "category": "Category, `updates` or `all`, `all` by default",
    "language": "Language, english by default, see below for more languages"
  },
  "path": "/news/:category?/:language?",
  "radar": [
    {
      "source": [
        "www.counter-strike.net/news",
        "www.counter-strike.net/"
      ],
      "target": "/news/all"
    },
    {
      "source": [
        "www.counter-strike.net/news/:category"
      ],
      "target": "/news/:category"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "#Blog_Title - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "76090323884335104",
      "image": "https://media.st.dl.eccdnx.com/apps/csgo/images/dota_react//blog/default_cover.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.counter-strike.net/news?l=english",
      "title": "Counter Strike - News",
      "type": "feed",
      "url": "rsshub://counter-strike/news"
    },
    {
      "description": "#Blog_Title - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "165244885864530944",
      "image": "https://media.st.dl.eccdnx.com/apps/csgo/images/dota_react//blog/default_cover.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.counter-strike.net/news/All?l=english",
      "title": "Counter Strike - News",
      "type": "feed",
      "url": "rsshub://counter-strike/news/All"
    }
  ],
  "url": "www.counter-strike.net"
}
```
