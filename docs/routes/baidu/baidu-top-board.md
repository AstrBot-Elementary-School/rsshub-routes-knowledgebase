# 百度 - 热搜榜单

## Coverage
`index-only`

## Route
- Namespace: `baidu`
- Namespace Name: `百度`
- Route Path: `/baidu/top/:board?`
- Route Name: `热搜榜单`
- Example: `/baidu/top`
- URL: `www.baidu.com`
- Language: `_None_`
- Categories: `other`
- Maintainers: `xyqfer`
- Source Location: `top.tsx`
- Source Module: `_None_`

## Description
| 热搜榜   | 小说榜 | 电影榜 | 电视剧榜 | 汽车榜 | 游戏榜 |
| -------- | ------ | ------ | -------- | ------ | ------ |
| realtime | novel  | movie  | teleplay | car    | game   |

## Parameters
- `board`: 榜单，默认为 `realtime`


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
    "other"
  ],
  "description": "| 热搜榜   | 小说榜 | 电影榜 | 电视剧榜 | 汽车榜 | 游戏榜 |\n| -------- | ------ | ------ | -------- | ------ | ------ |\n| realtime | novel  | movie  | teleplay | car    | game   |",
  "example": "/baidu/top",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 112,
  "location": "top.tsx",
  "maintainers": [
    "xyqfer"
  ],
  "name": "热搜榜单",
  "parameters": {
    "board": "榜单，默认为 `realtime`"
  },
  "path": "/top/:board?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "百度热搜以数亿用户海量的真实数据为基础，通过专业的数据挖掘方法，计算关键词的热搜指数，旨在建立权威、全面、热门、时效的各类关键词排行榜，引领热词阅读时代。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "55614129025417216",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://top.baidu.com/board?tab=realtime",
      "title": "热搜榜 - 百度热搜",
      "type": "feed",
      "url": "rsshub://baidu/top"
    },
    {
      "description": "百度热搜以数亿用户海量的真实数据为基础，通过专业的数据挖掘方法，计算关键词的热搜指数，旨在建立权威、全面、热门、时效的各类关键词排行榜，引领热词阅读时代。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "122089242504611840",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://top.baidu.com/board?tab=homepage",
      "title": "首页 - 百度热搜",
      "type": "feed",
      "url": "rsshub://baidu/top/homepage"
    }
  ]
}
```
