# 南京邮电大学 - 教务处通知与新闻

## Coverage
`index-only`

## Route
- Namespace: `njupt`
- Namespace Name: `南京邮电大学`
- Route Path: `/njupt/jwc/:type?`
- Route Name: `教务处通知与新闻`
- Example: `/njupt/jwc/notice`
- URL: `jwc.njupt.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `shaoye`
- Source Location: `jwc.ts`
- Source Module: `_None_`

## Description
| 通知公告 | 教务快讯 |
| -------- | -------- |
| notice   | news     |

## Parameters
- `type`: 默认为 `notice`


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
  "description": "| 通知公告 | 教务快讯 |\n| -------- | -------- |\n| notice   | news     |",
  "example": "/njupt/jwc/notice",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "jwc.ts",
  "maintainers": [
    "shaoye"
  ],
  "name": "教务处通知与新闻",
  "parameters": {
    "type": "默认为 `notice`"
  },
  "path": "/jwc/:type?",
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
