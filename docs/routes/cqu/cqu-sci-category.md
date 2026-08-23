# 重庆大学 - 数学与统计学院

## Coverage
`index-only`

## Route
- Namespace: `cqu`
- Namespace Name: `重庆大学`
- Route Path: `/cqu/sci/:category`
- Route Name: `数学与统计学院`
- Example: `/cqu/sci/xyxw`
- URL: `cqu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `Hagb`
- Source Location: `sci.ts`
- Source Module: `_None_`

## Description
| 学院新闻 | 学院公告 | 学院活动 | 学术活动 |
| -------- | -------- | -------- | -------- |
| xyxw     | xygg     | xyhd     | xshd1    |

## Parameters
- `category`: 分类名


## Features
- `requirePuppeteer`: true
- `antiCrawler`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 学院新闻 | 学院公告 | 学院活动 | 学术活动 |\n| -------- | -------- | -------- | -------- |\n| xyxw     | xygg     | xyhd     | xshd1    |",
  "example": "/cqu/sci/xyxw",
  "features": {
    "antiCrawler": true,
    "requirePuppeteer": true
  },
  "heat": 0,
  "location": "sci.ts",
  "maintainers": [
    "Hagb"
  ],
  "name": "数学与统计学院",
  "parameters": {
    "category": "分类名"
  },
  "path": "/sci/:category",
  "topFeeds": []
}
```
