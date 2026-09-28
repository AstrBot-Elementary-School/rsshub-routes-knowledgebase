# Tianjin University 天津大学 - Admission Office of Graduate

## Coverage
`index-only`

## Route
- Namespace: `tju`
- Namespace Name: `Tianjin University 天津大学`
- Route Path: `/tju/yzb/:type?`
- Route Name: `Admission Office of Graduate`
- Example: `/tju/yzb/notice`
- URL: `cic.tju.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `SuperPung`
- Source Location: `yzb/index.ts`
- Source Module: `_None_`

## Description
| School-level Notice | Master | Doctor | On-the-job Degree |
| :-----------------: | :----: | :----: | :---------------: |
|        notice       | master | doctor |        job        |

## Parameters
- `type`: default `notice`


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
  "description": "| School-level Notice | Master | Doctor | On-the-job Degree |\n| :-----------------: | :----: | :----: | :---------------: |\n|        notice       | master | doctor |        job        |",
  "example": "/tju/yzb/notice",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "yzb/index.ts",
  "maintainers": [
    "SuperPung"
  ],
  "name": "Admission Office of Graduate",
  "parameters": {
    "type": "default `notice`"
  },
  "path": "/yzb/:type?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "天津大学研究生招生网 - 校级公告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72241228347461632",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://yzb.tju.edu.cn/xwzx/zxxx/",
      "title": "天津大学研究生招生网 - 校级公告",
      "type": "feed",
      "url": "rsshub://tju/yzb/notice"
    },
    {
      "description": "天津大学研究生招生网 - 统考博士 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72241449526523904",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://yzb.tju.edu.cn/xwzx/tkbs_xw/",
      "title": "天津大学研究生招生网 - 统考博士",
      "type": "feed",
      "url": "rsshub://tju/yzb/doctor"
    }
  ]
}
```
