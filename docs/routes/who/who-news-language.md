# World Health Organization | WHO - News

## Coverage
`index-only`

## Route
- Namespace: `who`
- Namespace Name: `World Health Organization | WHO`
- Route Path: `/who/news/:language?`
- Route Name: `News`
- Example: `/who/news`
- URL: `who.int/news`
- Language: `_None_`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
Language

| English | العربية | 中文 | Français | Русский | Español | Português |
| ------- | ------- | ---- | -------- | ------- | ------- | --------- |
| en      | ar      | zh   | fr       | ru      | es      | pt        |

## Parameters
- `language`: Language, see below, English by default


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
  - `who.int/news`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "Language\n\n| English | العربية | 中文 | Français | Русский | Español | Português |\n| ------- | ------- | ---- | -------- | ------- | ------- | --------- |\n| en      | ar      | zh   | fr       | ru      | es      | pt        |",
  "example": "/who/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 9,
  "location": "news.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "News",
  "parameters": {
    "language": "Language, see below, English by default"
  },
  "path": "/news/:language?",
  "radar": [
    {
      "source": [
        "who.int/news"
      ],
      "target": "/news"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "News - WHO - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "80542799527249920",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.who.int/news",
      "title": "News - WHO",
      "type": "feed",
      "url": "rsshub://who/news"
    },
    {
      "description": "News - WHO - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "62422466958723072",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.who.int/zh/news",
      "title": "News - WHO",
      "type": "feed",
      "url": "rsshub://who/news/zh"
    }
  ],
  "url": "who.int/news"
}
```
