# 浙江大学 - 研究生院

## Coverage
`index-only`

## Route
- Namespace: `zju`
- Namespace Name: `浙江大学`
- Route Path: `/zju/grs/:type`
- Route Name: `研究生院`
- Example: `/zju/grs/1`
- URL: `physics.zju.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `Caicailiushui`
- Source Location: `grs/index.ts`
- Source Module: `_None_`

## Description
| 全部公告 | 教学管理 | 各类资助 | 学科建设 | 海外交流 |
| -------- | -------- | -------- | -------- | -------- |
| 1        | 2        | 3        | 4        | 5        |

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
  "description": "| 全部公告 | 教学管理 | 各类资助 | 学科建设 | 海外交流 |\n| -------- | -------- | -------- | -------- | -------- |\n| 1        | 2        | 3        | 4        | 5        |",
  "example": "/zju/grs/1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 6,
  "location": "grs/index.ts",
  "maintainers": [
    "Caicailiushui"
  ],
  "name": "研究生院",
  "parameters": {
    "type": "分类，见下表"
  },
  "path": "/grs/:type",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "浙大研究生院 -- 学科建设 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41965184796582001",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.grs.zju.edu.cn/xkjs/list.htm",
      "title": "浙大研究生院 -- 学科建设",
      "type": "feed",
      "url": "rsshub://zju/grs/4"
    },
    {
      "description": "浙大研究生院 -- 全部公告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41965184796582000",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.grs.zju.edu.cn/qbgg/list.htm",
      "title": "浙大研究生院 -- 全部公告",
      "type": "feed",
      "url": "rsshub://zju/grs/1"
    }
  ]
}
```
