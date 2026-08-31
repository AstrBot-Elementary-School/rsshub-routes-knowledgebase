# 南京信息工程大学 - NUIST ESE（南信大环科院）

## Coverage
`index-only`

## Route
- Namespace: `nuist`
- Namespace Name: `南京信息工程大学`
- Route Path: `/nuist/sese/:category?`
- Route Name: `NUIST ESE（南信大环科院）`
- Example: `/nuist/sese/tzgg1`
- URL: `bulletin.nuist.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `gylidian`
- Source Location: `sese.ts`
- Source Module: `_None_`

## Description
| 通知公告 | 新闻快讯 | 学术动态 | 学生工作 | 研究生教育 | 本科教育 |
| -------- | -------- | -------- | -------- | ---------- | -------- |
| tzgg1    | xwkx     | xsdt1    | xsgz1    | yjsjy1     | bkjy1    |

## Parameters
- `category`: 默认为通知公告


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
  "description": "| 通知公告 | 新闻快讯 | 学术动态 | 学生工作 | 研究生教育 | 本科教育 |\n| -------- | -------- | -------- | -------- | ---------- | -------- |\n| tzgg1    | xwkx     | xsdt1    | xsgz1    | yjsjy1     | bkjy1    |",
  "example": "/nuist/sese/tzgg1",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "sese.ts",
  "maintainers": [
    "gylidian"
  ],
  "name": "NUIST ESE（南信大环科院）",
  "parameters": {
    "category": "默认为通知公告"
  },
  "path": "/sese/:category?",
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
