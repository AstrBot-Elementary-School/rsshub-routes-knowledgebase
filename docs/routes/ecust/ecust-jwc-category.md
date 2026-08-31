# 华东理工大学 - 本科教务处信息网

## Coverage
`index-only`

## Route
- Namespace: `ecust`
- Namespace Name: `华东理工大学`
- Route Path: `/ecust/jwc/:category?`
- Route Name: `本科教务处信息网`
- Example: `/ecust/jwc/mto`
- URL: `e.ecust.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `lxl66566`
- Source Location: `jwc/notice.ts`
- Source Module: `_None_`

## Description
| 其他任意值 | mto          | mttb               | gi       | mpt          | fai          |
| ---------- | ------------ | ------------------ | -------- | ------------ | ------------ |
| 全部订阅   | 教学运行管理 | 培养与教学建设管理 | 综合信息 | 实践教学管理 | 学院教务信息 |

## Parameters
- `category`: 订阅板块，默认为全部订阅


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
  "description": "| 其他任意值 | mto          | mttb               | gi       | mpt          | fai          |\n| ---------- | ------------ | ------------------ | -------- | ------------ | ------------ |\n| 全部订阅   | 教学运行管理 | 培养与教学建设管理 | 综合信息 | 实践教学管理 | 学院教务信息 |",
  "example": "/ecust/jwc/mto",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "jwc/notice.ts",
  "maintainers": [
    "lxl66566"
  ],
  "name": "本科教务处信息网",
  "parameters": {
    "category": "订阅板块，默认为全部订阅"
  },
  "path": "/jwc/:category?",
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
