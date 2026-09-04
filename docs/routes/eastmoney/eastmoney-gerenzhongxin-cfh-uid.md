# 东方财富 - 个人中心长文

## Coverage
`index-only`

## Route
- Namespace: `eastmoney`
- Namespace Name: `东方财富`
- Route Path: `/eastmoney/gerenzhongxin/cfh/:uid`
- Route Name: `个人中心长文`
- Example: `/eastmoney/gerenzhongxin/cfh/2922094262312522`
- URL: `data.eastmoney.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `AwesomeDog`
- Source Location: `gerenzhongxin/cfh.ts`
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
- `target`: `/gerenzhongxin/cfh/:uid`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/eastmoney/gerenzhongxin/cfh/2922094262312522",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 24,
  "location": "gerenzhongxin/cfh.ts",
  "maintainers": [
    "AwesomeDog"
  ],
  "name": "个人中心长文",
  "parameters": {
    "uid": "用户id,即用户主页网址末尾的数字"
  },
  "path": "/gerenzhongxin/cfh/:uid",
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
      "target": "/gerenzhongxin/cfh/:uid"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "擒龙股海悟道 的东财长文 - Powered by RSSHub",
      "errorAt": "2026-09-03T04:33:05.655Z",
      "errorMessage": "Failed to fetch\n",
      "id": "211081391280129024",
      "image": "https://avator.eastmoney.com/qface/4927057225031910/360",
      "ownerUserId": null,
      "siteUrl": "https://i.eastmoney.com/4927057225031910#cfh",
      "title": "擒龙股海悟道 的东财长文",
      "type": "feed",
      "url": "rsshub://eastmoney/gerenzhongxin/cfh/4927057225031910"
    },
    {
      "description": "ST六点半 的东财长文 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "210695196280611840",
      "image": "https://avator.eastmoney.com/qface/6726346221702876/360",
      "ownerUserId": null,
      "siteUrl": "https://i.eastmoney.com/6726346221702876#cfh",
      "title": "ST六点半 的东财长文",
      "type": "feed",
      "url": "rsshub://eastmoney/gerenzhongxin/cfh/6726346221702876"
    }
  ],
  "view": 0
}
```
