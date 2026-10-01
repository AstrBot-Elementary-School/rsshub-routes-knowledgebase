# KBS - Today

## Coverage
`index-only`

## Route
- Namespace: `kbs`
- Namespace Name: `KBS`
- Route Path: `/kbs/today/:language?`
- Route Name: `Today`
- Example: `/kbs/today`
- URL: `world.kbs.co.kr/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `today.ts`
- Source Module: `_None_`

## Description
| 한국어 | عربي | 中国语 | English | Français | Deutsch | Bahasa Indonesia | 日本語 | Русский | Español | Tiếng Việt |
| ------ | ---- | ------ | ------- | -------- | ------- | ---------------- | ------ | ------- | ------- | ---------- |
| k      | a    | c      | e       | f        | g       | i                | j      | r       | s       | v          |

## Parameters
- `language`: Language, see below, e as English by default


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
  - `world.kbs.co.kr/`
- `target`: `/today`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 한국어 | عربي | 中国语 | English | Français | Deutsch | Bahasa Indonesia | 日本語 | Русский | Español | Tiếng Việt |\n| ------ | ---- | ------ | ------- | -------- | ------- | ---------------- | ------ | ------- | ------- | ---------- |\n| k      | a    | c      | e       | f        | g       | i                | j      | r       | s       | v          |",
  "example": "/kbs/today",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 7,
  "location": "today.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Today",
  "parameters": {
    "language": "Language, see below, e as English by default"
  },
  "path": "/today/:language?",
  "radar": [
    {
      "source": [
        "world.kbs.co.kr/"
      ],
      "target": "/today"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Latest News | KBS WORLD - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "69944407484189696",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://world.kbs.co.kr/service/news_today.htm?lang=c",
      "title": "Latest News | KBS WORLD",
      "type": "feed",
      "url": "rsshub://kbs/today/c"
    },
    {
      "description": "Latest News | KBS WORLD - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "69944115971721216",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://world.kbs.co.kr/service/news_today.htm?lang=e",
      "title": "Latest News | KBS WORLD",
      "type": "feed",
      "url": "rsshub://kbs/today"
    }
  ],
  "url": "world.kbs.co.kr/"
}
```
