# 东方财富 - 个人中心帖子

## Coverage
`index-only`

## Route
- Namespace: `eastmoney`
- Namespace Name: `东方财富`
- Route Path: `/eastmoney/gerenzhongxin/guba/:uid`
- Route Name: `个人中心帖子`
- Example: `/eastmoney/gerenzhongxin/guba/2922094262312522`
- URL: `data.eastmoney.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `AwesomeDog`
- Source Location: `gerenzhongxin/guba.ts`
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
- `target`: `/gerenzhongxin/guba/:uid`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/eastmoney/gerenzhongxin/guba/2922094262312522",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 7,
  "location": "gerenzhongxin/guba.ts",
  "maintainers": [
    "AwesomeDog"
  ],
  "name": "个人中心帖子",
  "parameters": {
    "uid": "用户id,即用户主页网址末尾的数字"
  },
  "path": "/gerenzhongxin/guba/:uid",
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
      "target": "/gerenzhongxin/guba/:uid"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "ST股猎手 的东财帖子 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "210564751338736640",
      "image": "https://avator.eastmoney.com/qface/6591057157855518/360",
      "ownerUserId": null,
      "siteUrl": "https://i.eastmoney.com/6591057157855518#guba",
      "title": "ST股猎手 的东财帖子",
      "type": "feed",
      "url": "rsshub://eastmoney/gerenzhongxin/guba/6591057157855518"
    },
    {
      "description": "ST小师妹 的东财帖子 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "210564241281737728",
      "image": "https://avator.eastmoney.com/qface/9032346035320658/360",
      "ownerUserId": null,
      "siteUrl": "https://i.eastmoney.com/9032346035320658#guba",
      "title": "ST小师妹 的东财帖子",
      "type": "feed",
      "url": "rsshub://eastmoney/gerenzhongxin/guba/9032346035320658"
    }
  ],
  "view": 0
}
```
