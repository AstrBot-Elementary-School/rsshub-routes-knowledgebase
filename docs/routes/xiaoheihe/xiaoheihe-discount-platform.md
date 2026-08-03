# 小黑盒 - 游戏折扣

## Coverage
`index-only`

## Route
- Namespace: `xiaoheihe`
- Namespace Name: `小黑盒`
- Route Path: `/xiaoheihe/discount/:platform`
- Route Name: `游戏折扣`
- Example: `/xiaoheihe/discount/pc`
- URL: `xiaoheihe.cn`
- Language: `_None_`
- Categories: `game`
- Maintainers: `tssujt`
- Source Location: `discount.ts`
- Source Module: `_None_`

## Description
| PC | Switch | PSN | Xbox |
| -- | ------ | --- | ---- |
| pc | switch | psn | xbox |

## Parameters
- `platform`: 平台分类，见下表


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
    "game"
  ],
  "description": "| PC | Switch | PSN | Xbox |\n| -- | ------ | --- | ---- |\n| pc | switch | psn | xbox |",
  "example": "/xiaoheihe/discount/pc",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 414,
  "location": "discount.ts",
  "maintainers": [
    "tssujt"
  ],
  "name": "游戏折扣",
  "parameters": {
    "platform": "平台分类，见下表"
  },
  "path": "/discount/:platform",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "小黑盒 PC 游戏折扣 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "78839970214681600",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://xiaoheihe.cn/",
      "title": "小黑盒 PC 游戏折扣",
      "type": "feed",
      "url": "rsshub://xiaoheihe/discount/pc"
    },
    {
      "description": "小黑盒 Switch 游戏折扣 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "86932279954497536",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://xiaoheihe.cn/",
      "title": "小黑盒 Switch 游戏折扣",
      "type": "feed",
      "url": "rsshub://xiaoheihe/discount/switch"
    }
  ]
}
```
