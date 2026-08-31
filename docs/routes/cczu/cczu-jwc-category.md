# 常州大学 - 教务处

## Coverage
`index-only`

## Route
- Namespace: `cczu`
- Namespace Name: `常州大学`
- Route Path: `/cczu/jwc/:category?`
- Route Name: `教务处`
- Example: `/cczu/jwc/1425`
- URL: `www.cczu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `stdrc`
- Source Location: `jwc.ts`
- Source Module: `_None_`

## Description
| 全部 | 通知公告 | 教务新闻 | 各类活动与系列讲座 | 本科教学工程 | 他山之石 | 信息快递 |
| ---- | -------- | -------- | ------------------ | ------------ | -------- | -------- |
| all  | 1425     | 1437     | 1485               | 1487         | 1442     | 1445     |

## Parameters
- `category`: 可选，默认为 `all`


## Features
- `antiCrawler`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 全部 | 通知公告 | 教务新闻 | 各类活动与系列讲座 | 本科教学工程 | 他山之石 | 信息快递 |\n| ---- | -------- | -------- | ------------------ | ------------ | -------- | -------- |\n| all  | 1425     | 1437     | 1485               | 1487         | 1442     | 1445     |",
  "example": "/cczu/jwc/1425",
  "features": {
    "antiCrawler": true
  },
  "heat": 0,
  "location": "jwc.ts",
  "maintainers": [
    "stdrc"
  ],
  "name": "教务处",
  "parameters": {
    "category": "可选，默认为 `all`"
  },
  "path": "/jwc/:category?",
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
