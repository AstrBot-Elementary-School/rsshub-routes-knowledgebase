# 山东大学 - 核科学与能源动力学院通知

## Coverage
`index-only`

## Route
- Namespace: `sdu`
- Namespace Name: `山东大学`
- Route Path: `/sdu/epe/:type?`
- Route Name: `核科学与能源动力学院通知`
- Example: `/sdu/epe/0`
- URL: `www.sdu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `Ji4n1ng`
- Source Location: `epe.ts`
- Source Module: `_None_`

## Description
| 学院动态 | 通知公告 | 学术动态 |
| -------- | -------- | -------- |
| 0        | 1        | 2        |

## Parameters
- `type`: 默认为 `0`


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
  "description": "| 学院动态 | 通知公告 | 学术动态 |\n| -------- | -------- | -------- |\n| 0        | 1        | 2        |",
  "example": "/sdu/epe/0",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "epe.ts",
  "maintainers": [
    "Ji4n1ng"
  ],
  "name": "核科学与能源动力学院通知",
  "parameters": {
    "type": "默认为 `0`"
  },
  "path": "/epe/:type?",
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
