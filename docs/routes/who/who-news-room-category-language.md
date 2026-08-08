# World Health Organization | WHO - Newsroom

## Coverage
`index-only`

## Route
- Namespace: `who`
- Namespace Name: `World Health Organization | WHO`
- Route Path: `/who/news-room/:category?/:language?`
- Route Name: `Newsroom`
- Example: `/who/news-room/feature-stories`
- URL: `who.int/news`
- Language: `_None_`
- Categories: `government`
- Maintainers: `LogicJake, nczitzk`
- Source Location: `news-room.ts`
- Source Module: `_None_`

## Description
Category

| Feature stories | Commentaries |
| --------------- | ------------ |
| feature-stories | commentaries |

Language

| English | العربية | 中文 | Français | Русский | Español | Português |
| ------- | ------- | ---- | -------- | ------- | ------- | --------- |
| en      | ar      | zh   | fr       | ru      | es      | pt        |

## Parameters
- `category`: Category, see below, Feature stories by default
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
  - `who.int/news-room/:type`
- `target`: `/news-room/:type`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "Category\n\n| Feature stories | Commentaries |\n| --------------- | ------------ |\n| feature-stories | commentaries |\n\nLanguage\n\n| English | العربية | 中文 | Français | Русский | Español | Português |\n| ------- | ------- | ---- | -------- | ------- | ------- | --------- |\n| en      | ar      | zh   | fr       | ru      | es      | pt        |",
  "example": "/who/news-room/feature-stories",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 8,
  "location": "news-room.ts",
  "maintainers": [
    "LogicJake",
    "nczitzk"
  ],
  "name": "Newsroom",
  "parameters": {
    "category": "Category, see below, Feature stories by default",
    "language": "Language, see below, English by default"
  },
  "path": "/news-room/:category?/:language?",
  "radar": [
    {
      "source": [
        "who.int/news-room/:type"
      ],
      "target": "/news-room/:type"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Feature stories - WHO - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "62422399410744320",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.who.int/news-room/feature-stories",
      "title": "Feature stories - WHO",
      "type": "feed",
      "url": "rsshub://who/news-room/feature-stories"
    },
    {
      "description": "评论 - WHO - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "94224807176272896",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.who.int/zh/news-room/commentaries",
      "title": "评论 - WHO",
      "type": "feed",
      "url": "rsshub://who/news-room/commentaries/zh"
    }
  ],
  "url": "who.int/news"
}
```
