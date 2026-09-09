# Tianjin University 天津大学 - College of Intelligence and Computing

## Coverage
`index-only`

## Route
- Namespace: `tju`
- Namespace Name: `Tianjin University 天津大学`
- Route Path: `/tju/cic/:type?`
- Route Name: `College of Intelligence and Computing`
- Example: `/tju/cic/news`
- URL: `cic.tju.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `AlanZeng423, SuperPung`
- Source Location: `cic/index.ts`
- Source Module: `_None_`

## Description
| College News | Notification | TJU Forum for CIC |
| :----------: | :----------: | :---------------: |
|     news     | notification |       forum       |

## Parameters
- `type`: default `news`


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
  "description": "| College News | Notification | TJU Forum for CIC |\n| :----------: | :----------: | :---------------: |\n|     news     | notification |       forum       |",
  "example": "/tju/cic/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "cic/index.ts",
  "maintainers": [
    "AlanZeng423",
    "SuperPung"
  ],
  "name": "College of Intelligence and Computing",
  "parameters": {
    "type": "default `news`"
  },
  "path": "/cic/:type?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "天津大学智能与计算学部 - 学部新闻 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "65092029340802048",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://cic.tju.edu.cn/xwzx/xyxw.htm",
      "title": "天津大学智能与计算学部 - 学部新闻",
      "type": "feed",
      "url": "rsshub://tju/cic/news"
    },
    {
      "description": "天津大学智能与计算学部 - 通知公告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "65092198815849472",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://cic.tju.edu.cn/xwzx/tzgg.htm",
      "title": "天津大学智能与计算学部 - 通知公告",
      "type": "feed",
      "url": "rsshub://tju/cic/notification"
    }
  ]
}
```
