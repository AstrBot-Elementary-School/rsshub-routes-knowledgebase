# 中南大学 - 计算机学院

## Coverage
`index-only`

## Route
- Namespace: `csu`
- Namespace Name: `中南大学`
- Route Path: `/csu/cse/:type?`
- Route Name: `计算机学院`
- Example: `/csu/cse`
- URL: `career.csu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `j1g5awi`
- Source Location: `cse.ts`
- Source Module: `_None_`

## Description
| 类型 | 学院新闻 | 通知公告 | 学术信息 | 学工动态 | 科研动态 |
| ---- | -------- | -------- | -------- | -------- | -------- |
| 参数 | xyxw     | tzgg     | xsxx     | xgdt     | kydt     |

## Parameters
- `type`: 类型


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
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
  "description": "| 类型 | 学院新闻 | 通知公告 | 学术信息 | 学工动态 | 科研动态 |\n| ---- | -------- | -------- | -------- | -------- | -------- |\n| 参数 | xyxw     | tzgg     | xsxx     | xgdt     | kydt     |",
  "example": "/csu/cse",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "cse.ts",
  "maintainers": [
    "j1g5awi"
  ],
  "name": "计算机学院",
  "parameters": {
    "type": "类型"
  },
  "path": "/cse/:type?",
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
