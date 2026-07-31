# 游讯网 - 资讯

## Coverage
`index-only`

## Route
- Namespace: `yxdown`
- Namespace Name: `游讯网`
- Route Path: `/yxdown/news/:category?`
- Route Name: `资讯`
- Example: `/yxdown/news`
- URL: `yxdown.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `nczitzk`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| 资讯首页 | 业界动态 | 视频预告 | 新作发布 | 游戏资讯 | 游戏评测 | 网络游戏 | 手机游戏 |
| -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
|          | dongtai  | yugao    | xinzuo   | zixun    | pingce   | wangluo  | shouyou  |

## Parameters
- `category`: 分类，见下表，默认为资讯首页


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
  "description": "| 资讯首页 | 业界动态 | 视频预告 | 新作发布 | 游戏资讯 | 游戏评测 | 网络游戏 | 手机游戏 |\n| -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |\n|          | dongtai  | yugao    | xinzuo   | zixun    | pingce   | wangluo  | shouyou  |",
  "example": "/yxdown/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "news.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "资讯",
  "parameters": {
    "category": "分类，见下表，默认为资讯首页"
  },
  "path": "/news/:category?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-08-11T10:10:27.202Z",
      "errorMessage": "Cannot read properties of null (reading '0')\n",
      "id": "177651896292778038",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://yxdown/news"
    }
  ]
}
```
