# KBS - News

## Coverage
`index-only`

## Route
- Namespace: `kbs`
- Namespace Name: `KBS`
- Route Path: `/kbs/news/:category?/:language?`
- Route Name: `News`
- Example: `/kbs/news`
- URL: `world.kbs.co.kr/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| 한국어 | عربي | 中国语 | English | Français | Deutsch | Bahasa Indonesia | 日本語 | Русский | Español | Tiếng Việt |
| ------ | ---- | ------ | ------- | -------- | ------- | ---------------- | ------ | ------- | ------- | ---------- |
| k      | a    | c      | e       | f        | g       | i                | j      | r       | s       | v          |

## Parameters
- `category`: Category, can be found in Url as `id`, all by default
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
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 한국어 | عربي | 中国语 | English | Français | Deutsch | Bahasa Indonesia | 日本語 | Русский | Español | Tiếng Việt |\n| ------ | ---- | ------ | ------- | -------- | ------- | ---------------- | ------ | ------- | ------- | ---------- |\n| k      | a    | c      | e       | f        | g       | i                | j      | r       | s       | v          |",
  "example": "/kbs/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 21,
  "location": "news.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "News",
  "parameters": {
    "category": "Category, can be found in Url as `id`, all by default",
    "language": "Language, see below, e as English by default"
  },
  "path": "/news/:category?/:language?",
  "radar": [
    {
      "source": [
        "world.kbs.co.kr/"
      ],
      "target": "/news"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "All - KBS WORLD - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "69944188878743552",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://world.kbs.co.kr/service/news_list.htm?lang=e",
      "title": "All - KBS WORLD",
      "type": "feed",
      "url": "rsshub://kbs/news"
    },
    {
      "description": "全部 - KBS WORLD - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "62963988811276288",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://world.kbs.co.kr/service/news_list.htm?lang=c",
      "title": "全部 - KBS WORLD",
      "type": "feed",
      "url": "rsshub://kbs/news/all/c"
    }
  ],
  "url": "world.kbs.co.kr/"
}
```
