# Hpoi 手办维基 - 所有周边

## Coverage
`index-only`

## Route
- Namespace: `hpoi`
- Namespace Name: `Hpoi 手办维基`
- Route Path: `/hpoi/items/all/:order?`
- Route Name: `所有周边`
- Example: `/hpoi/items/all`
- URL: `www.hpoi.net/hobby/all`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `DIYgod`
- Source Location: `all.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `order`: {"default": "add", "description": "排序", "options": [{"label": "发售", "value": "release"}, {"label": "入库", "value": "add"}, {"label": "总热度", "value": "hits"}, {"label": "一周热度", "value": "hits7Day"}, {"label": "一天热度", "value": "hitsDay"}, {"label": "评价", "value": "rating"}]}


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
  - `www.hpoi.net/hobby/all`
- `target`: `/items/all`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/hpoi/items/all",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 456,
  "location": "all.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "所有周边",
  "parameters": {
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
  "path": "/items/all/:order?",
  "radar": [
    {
      "source": [
        "www.hpoi.net/hobby/all"
      ],
      "target": "/items/all"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Hpoi 手办维基 - 全部周边 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "58853176014049280",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.hpoi.net/hobby/all?order=add&r18=-1",
      "title": "Hpoi 手办维基 - 全部周边",
      "type": "feed",
      "url": "rsshub://hpoi/items/all/add"
    },
    {
      "description": "Hpoi 手办维基 - 全部周边 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41147805268337673",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.hpoi.net/hobby/all?order=hits7Day&r18=-1",
      "title": "Hpoi 手办维基 - 全部周边",
      "type": "feed",
      "url": "rsshub://hpoi/items/all/hits7Day"
    }
  ],
  "url": "www.hpoi.net/hobby/all",
  "view": 2
}
```
