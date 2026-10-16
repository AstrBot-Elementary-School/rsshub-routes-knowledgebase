# 深圳市人民政府 - 住房和建设局

## Coverage
`index-only`

## Route
- Namespace: `gov/shenzhen`
- Namespace Name: `深圳市人民政府`
- Route Path: `/gov/shenzhen/zjj/xxgk/:caty`
- Route Name: `住房和建设局`
- Example: `/gov/shenzhen/zjj/xxgk/tzgg`
- URL: `www.sz.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `lonn`
- Source Location: `zjj/index.ts`
- Source Module: `_None_`

## Description
| 通知公告 |
| :------: |
|   tzgg   |

## Parameters
- `caty`: 信息类别


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
  - `zjj.sz.gov.cn/xxgk/:caty`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 通知公告 |\n| :------: |\n|   tzgg   |",
  "example": "/gov/shenzhen/zjj/xxgk/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 11,
  "location": "zjj/index.ts",
  "maintainers": [
    "lonn"
  ],
  "name": "住房和建设局",
  "parameters": {
    "caty": "信息类别"
  },
  "path": "/zjj/xxgk/:caty",
  "radar": [
    {
      "source": [
        "zjj.sz.gov.cn/xxgk/:caty"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "深圳市住房和建设局 - 通知公告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "69966067980854272",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://zjj.sz.gov.cn/xxgk/tzgg/",
      "title": "深圳市住房和建设局 - 通知公告",
      "type": "feed",
      "url": "rsshub://gov/shenzhen/zjj/xxgk/tzgg"
    }
  ]
}
```
