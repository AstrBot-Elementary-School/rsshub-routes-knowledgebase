# iThome 台灣 - 专题

## Coverage
`index-only`

## Route
- Namespace: `ithome`
- Namespace Name: `iThome 台灣`
- Route Path: `/ithome/zt/:id?`
- Route Name: `专题`
- Example: `/ithome/zt/xijiayi`
- URL: `ithome.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `zt.tsx`
- Source Module: `_None_`

## Description
::: tip
更多专题请见 [IT 之家专题](https://www.ithome.com/zt)
:::

## Parameters
- `category`: 专题 id，默认为 xijiayi，即 [喜加一](https://www.ithome.com/zt/xijiayi)，可在对应专题页 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `ithome.com/zt/:id`
- `target`: `/zt/:id`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\n更多专题请见 [IT 之家专题](https://www.ithome.com/zt)\n:::",
  "example": "/ithome/zt/xijiayi",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 60,
  "location": "zt.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "专题",
  "parameters": {
    "category": "专题 id，默认为 xijiayi，即 [喜加一](https://www.ithome.com/zt/xijiayi)，可在对应专题页 URL 中找到"
  },
  "path": "/zt/:id?",
  "radar": [
    {
      "source": [
        "ithome.com/zt/:id"
      ],
      "target": "/zt/:id"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "最新最全的「喜加一」游戏动态尽在这里！ - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "65331190227109888",
      "image": "https://www.ithome.com/undefined",
      "ownerUserId": null,
      "siteUrl": "https://www.ithome.com/zt/xijiayi",
      "title": "IT之家 - 「喜加一」最新动态",
      "type": "feed",
      "url": "rsshub://ithome/zt/xijiayi"
    },
    {
      "description": "最新最全的「喜加一」游戏动态尽在这里！ - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "234520551305109504",
      "image": "https://www.ithome.com/undefined",
      "ownerUserId": null,
      "siteUrl": "https://www.ithome.com/zt/xijiayi",
      "title": "IT之家 - 「喜加一」最新动态",
      "type": "feed",
      "url": "rsshub://ithome/zt"
    }
  ],
  "url": "ithome.com"
}
```
