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
      "description": "二萌Alice 的动态 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "92101048147199003",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://ds.163.com/user/3ccb247ef47a4a8480ad9d1b7a239a05",
      "title": "二萌Alice 的动态",
      "type": "feed",
      "url": "rsshub://163/ds/3ccb247ef47a4a8480ad9d1b7a239a05"
    },
    {
      "description": "DatahunterSora 的动态 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "92101048147199002",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://ds.163.com/user/6d8b6fe852fe4dda86723c6fa24a266f",
      "title": "DatahunterSora 的动态",
      "type": "feed",
      "url": "rsshub://163/ds/6d8b6fe852fe4dda86723c6fa24a266f"
    }
  ]
}
```
