# 东方财富 - 个人中心所有活动

## Coverage
`index-only`

## Route
- Namespace: `eastmoney`
- Namespace Name: `东方财富`
- Route Path: `/eastmoney/gerenzhongxin/gather/:uid`
- Route Name: `个人中心所有活动`
- Example: `/eastmoney/gerenzhongxin/gather/2922094262312522`
- URL: `data.eastmoney.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `AwesomeDog`
- Source Location: `gerenzhongxin/gather.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `uid`: 用户id,即用户主页网址末尾的数字


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
  - `guba.eastmoney.com`
### Rule 2
- `source`:
  - `caifuhao.eastmoney.com`
### Rule 3
- `source`:
  - `i.eastmoney.com/:uid`
- `target`: `/gerenzhongxin/gather/:uid`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/eastmoney/gerenzhongxin/gather/2922094262312522",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "gerenzhongxin/gather.ts",
  "maintainers": [
    "AwesomeDog"
  ],
  "name": "个人中心所有活动",
  "parameters": {
    "uid": "用户id,即用户主页网址末尾的数字"
  },
  "path": "/gerenzhongxin/gather/:uid",
  "radar": [
    {
      "source": [
        "guba.eastmoney.com"
      ]
    },
    {
      "source": [
        "caifuhao.eastmoney.com"
      ]
    },
    {
      "source": [
        "i.eastmoney.com/:uid"
      ],
      "target": "/gerenzhongxin/gather/:uid"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "风浪越大越精神 的东财所有活动 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "1160269964720865280",
      "image": "https://avator.eastmoney.com/qface/4571315979945492/360",
      "ownerUserId": null,
      "siteUrl": "https://i.eastmoney.com/4571315979945492",
      "title": "风浪越大越精神 的东财所有活动",
      "type": "feed",
      "url": "rsshub://eastmoney/gerenzhongxin/gather/4571315979945492"
    }
  ],
  "view": 0
}
```
