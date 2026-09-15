# Komiic - 漫画更新

## Coverage
`index-only`

## Route
- Namespace: `komiic`
- Namespace Name: `Komiic`
- Route Path: `/komiic/comic/:id`
- Route Name: `漫画更新`
- Example: `/komiic/comic/533`
- URL: `komiic.com`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `NekoAria`
- Source Location: `comic.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 漫画 ID


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `komiic.com/comic/:id`
- `target`: `/comic/:id`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/komiic/comic/533",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 46,
  "location": "comic.ts",
  "maintainers": [
    "NekoAria"
  ],
  "name": "漫画更新",
  "parameters": {
    "id": "漫画 ID"
  },
  "path": "/comic/:id",
  "radar": [
    {
      "source": [
        "komiic.com/comic/:id"
      ],
      "target": "/comic/:id"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Komiic - 葬送的芙莉蓮 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "127563545770234880",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://komiic.com/comic/217",
      "title": "Komiic - 葬送的芙莉蓮",
      "type": "feed",
      "url": "rsshub://komiic/comic/217"
    },
    {
      "description": "Komiic - 魔都精兵的奴隸 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "118075271617970176",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://komiic.com/comic/533",
      "title": "Komiic - 魔都精兵的奴隸",
      "type": "feed",
      "url": "rsshub://komiic/comic/533"
    }
  ]
}
```
