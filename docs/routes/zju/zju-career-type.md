# 浙江大学 - 就业服务平台

## Coverage
`index-only`

## Route
- Namespace: `zju`
- Namespace Name: `浙江大学`
- Route Path: `/zju/career/:type`
- Route Name: `就业服务平台`
- Example: `/zju/career/1`
- URL: `physics.zju.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `Caicailiushui`
- Source Location: `career/index.ts`
- Source Module: `_None_`

## Description
| 新闻动态 | 活动通知 | 学院通知 | 告示通知 |
| -------- | -------- | -------- | -------- |
| 1        | 2        | 3        | 4        |

## Parameters
- `type`: 分类，见下表


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
    "university"
  ],
  "description": "| 新闻动态 | 活动通知 | 学院通知 | 告示通知 |\n| -------- | -------- | -------- | -------- |\n| 1        | 2        | 3        | 4        |",
  "example": "/zju/career/1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 4,
  "location": "career/index.ts",
  "maintainers": [
    "Caicailiushui"
  ],
  "name": "就业服务平台",
  "parameters": {
    "type": "分类，见下表"
  },
  "path": "/career/:type",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "浙大就业服务平台 -- 新闻动态 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41965184796582002",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.career.zju.edu.cn/jyxt/jygz/new/getContent.zf?minCount=0&maxCount=10&lmjdid=739BEBB72A072B25E0538713470A6C41&sjlmid=undefined&lmtype=2&lx=2",
      "title": "浙大就业服务平台 -- 新闻动态",
      "type": "feed",
      "url": "rsshub://zju/career/1"
    },
    {
      "description": "浙大就业服务平台 -- 告示通告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41965184796582024",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.career.zju.edu.cn/jyxt/jygz/new/getContent.zf?minCount=0&maxCount=10&lmjdid=739BEBB72A252B25E0538713470A6C41&sjlmid=undefined&lmtype=2&lx=2",
      "title": "浙大就业服务平台 -- 告示通告",
      "type": "feed",
      "url": "rsshub://zju/career/4"
    }
  ]
}
```
