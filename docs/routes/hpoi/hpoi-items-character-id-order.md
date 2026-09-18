# Hpoi 手办维基 - 角色周边

## Coverage
`index-only`

## Route
- Namespace: `hpoi`
- Namespace Name: `Hpoi 手办维基`
- Route Path: `/hpoi/items/character/:id/:order?`
- Route Name: `角色周边`
- Example: `/hpoi/items/character/1035374`
- URL: `www.hpoi.net`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `DIYgod`
- Source Location: `character.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 角色 ID
- `order`: {"default": "add", "description": "排序", "options": [{"label": "发售", "value": "release"}, {"label": "入库", "value": "add"}, {"label": "总热度", "value": "hits"}, {"label": "一周热度", "value": "hits7Day"}, {"label": "一天热度", "value": "hitsDay"}, {"label": "评价", "value": "rating"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/hpoi/items/character/1035374",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 16,
  "location": "character.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "角色周边",
  "parameters": {
    "id": "角色 ID",
    "order": {
      "default": "add",
      "description": "排序",
      "options": [
        {
          "label": "发售",
          "value": "release"
        },
        {
          "label": "入库",
          "value": "add"
        },
        {
          "label": "总热度",
          "value": "hits"
        },
        {
          "label": "一周热度",
          "value": "hits7Day"
        },
        {
          "label": "一天热度",
          "value": "hitsDay"
        },
        {
          "label": "评价",
          "value": "rating"
        }
      ]
    }
  },
  "path": "/items/character/:id/:order?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Hpoi 手办维基 - 角色周边 1035374 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59118527455044608",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.hpoi.net/hobby/all?order=add&r18=-1&charactar=1035374",
      "title": "Hpoi 手办维基 - 角色周边 1035374",
      "type": "feed",
      "url": "rsshub://hpoi/items/character/1035374"
    },
    {
      "description": "Hpoi 手办维基 - 角色周边 4651 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "62525153362050048",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.hpoi.net/hobby/all?order=release&r18=-1&charactar=4651",
      "title": "Hpoi 手办维基 - 角色周边 4651",
      "type": "feed",
      "url": "rsshub://hpoi/items/character/4651/release"
    }
  ],
  "view": 2
}
```
