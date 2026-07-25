# 金十数据 - 市场快讯

## Coverage
`index-only`

## Route
- Namespace: `jin10`
- Namespace Name: `金十数据`
- Route Path: `/jin10/:important?`
- Route Name: `市场快讯`
- Example: `/jin10`
- URL: `jin10.com/`
- Language: `_None_`
- Categories: `finance, popular`
- Maintainers: `laampui`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `important`: 只看重要，任意值开启，留空关闭


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
  - `jin10.com/`
- `target`: ``

## Raw JSON
```json
{
  "categories": [
    "finance",
    "popular"
  ],
  "example": "/jin10",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2505,
  "location": "index.ts",
  "maintainers": [
    "laampui"
  ],
  "name": "市场快讯",
  "parameters": {
    "important": "只看重要，任意值开启，留空关闭"
  },
  "path": "/:important?",
  "radar": [
    {
      "source": [
        "jin10.com/"
      ],
      "target": ""
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "金十数据 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "44366244616936448",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.jin10.com/",
      "title": "金十数据",
      "type": "feed",
      "url": "rsshub://jin10"
    },
    {
      "description": "金十数据 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72573375336611840",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.jin10.com/",
      "title": "金十数据",
      "type": "feed",
      "url": "rsshub://jin10/1"
    }
  ],
  "url": "jin10.com/",
  "view": 5
}
```
