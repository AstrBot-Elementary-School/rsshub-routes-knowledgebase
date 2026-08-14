# 网易公开课 - 用户发帖

## Coverage
`index-only`

## Route
- Namespace: `163`
- Namespace Name: `网易公开课`
- Route Path: `/163/ds/:id`
- Route Name: `用户发帖`
- Example: `/163/ds/63dfbaf4117741daaf73404601165843`
- URL: `163.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `luyuhuang`
- Source Location: `ds.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 用户ID


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
  - `ds.163.com/user/:id`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/163/ds/63dfbaf4117741daaf73404601165843",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 10,
  "location": "ds.tsx",
  "maintainers": [
    "luyuhuang"
  ],
  "name": "用户发帖",
  "parameters": {
    "id": "用户ID"
  },
  "path": "/ds/:id",
  "radar": [
    {
      "source": [
        "ds.163.com/user/:id"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "暴雪大神 的动态 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "92101048147198999",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://ds.163.com/user/13be30b3f5204a17b3e52eaf9f0e44aa",
      "title": "暴雪大神 的动态",
      "type": "feed",
      "url": "rsshub://163/ds/13be30b3f5204a17b3e52eaf9f0e44aa"
    },
    {
      "description": "魔兽客服公告 的动态 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "166489281655090183",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://ds.163.com/user/a3d082651b054b4d8a79dd327f893a94",
      "title": "魔兽客服公告 的动态",
      "type": "feed",
      "url": "rsshub://163/ds/a3d082651b054b4d8a79dd327f893a94"
    }
  ]
}
```
