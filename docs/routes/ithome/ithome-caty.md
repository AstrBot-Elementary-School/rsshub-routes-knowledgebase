# iThome 台灣 - 分类资讯

## Coverage
`index-only`

## Route
- Namespace: `ithome`
- Namespace Name: `iThome 台灣`
- Route Path: `/ithome/:caty`
- Route Name: `分类资讯`
- Example: `/ithome/it`
- URL: `ithome.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `luyuhuang`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| it      | soft     | win10      | win11      | iphone      | ipad      | android      | digi     | next     |
| ------- | -------- | ---------- | ---------- | ----------- | --------- | ------------ | -------- | -------- |
| IT 资讯 | 软件之家 | win10 之家 | win11 之家 | iphone 之家 | ipad 之家 | android 之家 | 数码之家 | 智能时代 |

## Parameters
- `caty`: 类别


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
    "new-media"
  ],
  "description": "| it      | soft     | win10      | win11      | iphone      | ipad      | android      | digi     | next     |\n| ------- | -------- | ---------- | ---------- | ----------- | --------- | ------------ | -------- | -------- |\n| IT 资讯 | 软件之家 | win10 之家 | win11 之家 | iphone 之家 | ipad 之家 | android 之家 | 数码之家 | 智能时代 |",
  "example": "/ithome/it",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 249,
  "location": "index.ts",
  "maintainers": [
    "luyuhuang"
  ],
  "name": "分类资讯",
  "parameters": {
    "caty": "类别"
  },
  "path": "/:caty",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "IT 之家 - IT 资讯 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41572238273905677",
      "image": "https://img.ithome.com/m/images/logo.png",
      "ownerUserId": null,
      "siteUrl": "https://it.ithome.com/",
      "title": "IT 之家 - IT 资讯",
      "type": "feed",
      "url": "rsshub://ithome/it"
    },
    {
      "description": "IT 之家 - 数码之家 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41572238273905673",
      "image": "https://img.ithome.com/m/images/logo.png",
      "ownerUserId": null,
      "siteUrl": "https://digi.ithome.com/",
      "title": "IT 之家 - 数码之家",
      "type": "feed",
      "url": "rsshub://ithome/digi"
    }
  ]
}
```
