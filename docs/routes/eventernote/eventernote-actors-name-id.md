# Eventernote - 声优活动及演唱会

## Coverage
`index-only`

## Route
- Namespace: `eventernote`
- Namespace Name: `Eventernote`
- Route Path: `/eventernote/actors/:name/:id`
- Route Name: `声优活动及演唱会`
- Example: `/eventernote/actors/三森すずこ/2634`
- URL: `www.eventernote.com`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `KTachibanaM`
- Source Location: `actors.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `name`: 声优姓名
- `id`: 声优 ID


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
  - `www.eventernote.com/actors/:name/:id`
  - `www.eventernote.com/actors/:name/:id/events`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/eventernote/actors/三森すずこ/2634",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 47,
  "location": "actors.ts",
  "maintainers": [
    "KTachibanaM"
  ],
  "name": "声优活动及演唱会",
  "parameters": {
    "id": "声优 ID",
    "name": "声优姓名"
  },
  "path": "/actors/:name/:id",
  "radar": [
    {
      "source": [
        "www.eventernote.com/actors/:name/:id",
        "www.eventernote.com/actors/:name/:id/events"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "MyGO!!!!!のイベント・ライブ情報一覧 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "73913698350104576",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.eventernote.com/actors/MyGO!!!!!/66346/events",
      "title": "MyGO!!!!!のイベント・ライブ情報一覧",
      "type": "feed",
      "url": "rsshub://eventernote/actors/MyGO%21%21%21%21%21/66346"
    },
    {
      "description": "Liyuu(黎獄)のイベント・ライブ情報一覧 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "73398154092254208",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.eventernote.com/actors/Liyuu(%E9%BB%8E%E7%8D%84)/34637/events",
      "title": "Liyuu(黎獄)のイベント・ライブ情報一覧",
      "type": "feed",
      "url": "rsshub://eventernote/actors/Liyuu(%E9%BB%8E%E7%8D%84)/34637"
    }
  ],
  "view": 3
}
```
