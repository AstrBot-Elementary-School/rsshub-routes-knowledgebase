# 游戏日报 - 分类

## Coverage
`index-only`

## Route
- Namespace: `yxrb`
- Namespace Name: `游戏日报`
- Route Path: `/yxrb/:category?`
- Route Name: `分类`
- Example: `/yxrb/info`
- URL: `news.yxrb.net`
- Language: `_None_`
- Categories: `game`
- Maintainers: `TonyRL`
- Source Location: `home.ts`
- Source Module: `_None_`

## Description
| 资讯 | 访谈    | 服务    | 游理游据 |
| ---- | ------- | ------- | -------- |
| info | talking | service | comments |

## Parameters
- `category`: 分类，见下表，预设为 `info`


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
  - `news.yxrb.net/:category`
  - `news.yxrb.net/`
- `target`: `/:category`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "| 资讯 | 访谈    | 服务    | 游理游据 |\n| ---- | ------- | ------- | -------- |\n| info | talking | service | comments |",
  "example": "/yxrb/info",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 136,
  "location": "home.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "分类",
  "parameters": {
    "category": "分类，见下表，预设为 `info`"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "news.yxrb.net/:category",
        "news.yxrb.net/"
      ],
      "target": "/:category"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "游戏资讯, 游戏日报提供最具价值行业信息。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "56176972513891328",
      "image": "http://news.yxrb.net/uploadfile/2022/1008/8daa67f624b4928.png",
      "ownerUserId": null,
      "siteUrl": "http://news.yxrb.net/info/",
      "title": "资讯 - 游戏日报",
      "type": "feed",
      "url": "rsshub://yxrb/info"
    },
    {
      "description": "游戏资讯, 游戏日报提供最具价值行业信息。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "93963104693017600",
      "image": "http://news.yxrb.net/uploadfile/2022/1008/8daa67f624b4928.png",
      "ownerUserId": null,
      "siteUrl": "http://news.yxrb.net/info/",
      "title": "资讯 - 游戏日报",
      "type": "feed",
      "url": "rsshub://yxrb"
    }
  ]
}
```
