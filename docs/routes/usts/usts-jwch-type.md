# 苏州科技大学 - 教务处

## Coverage
`index-only`

## Route
- Namespace: `usts`
- Namespace Name: `苏州科技大学`
- Route Path: `/usts/jwch/:type?`
- Route Name: `教务处`
- Example: `/usts/jwch`
- URL: `jwch.usts.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `Fatpandac`
- Source Location: `jwch.ts`
- Source Module: `_None_`

## Description
| 类型 | 教务动态 | 公告在线 | 选课通知 |
| ---- | -------- | -------- | -------- |
|      | jwdt     | ggzx     | xktz     |

## Parameters
- `type`: 类型，默认为教务动态


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
  "description": "| 类型 | 教务动态 | 公告在线 | 选课通知 |\n| ---- | -------- | -------- | -------- |\n|      | jwdt     | ggzx     | xktz     |",
  "example": "/usts/jwch",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "jwch.ts",
  "maintainers": [
    "Fatpandac"
  ],
  "name": "教务处",
  "parameters": {
    "type": "类型，默认为教务动态"
  },
  "path": "/jwch/:type?",
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
