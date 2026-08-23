# 云南大学 - 教务处主要通知

## Coverage
`index-only`

## Route
- Namespace: `ynu`
- Namespace Name: `云南大学`
- Route Path: `/ynu/jwc/:category`
- Route Name: `教务处主要通知`
- Example: `/ynu/jwc/1`
- URL: `www.ynu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `hzcheney`
- Source Location: `jwc/zytz.ts`
- Source Module: `_None_`

## Description
| 教务科 | 学籍科 | 教学研究科 | 实践科学科 |
| ------ | ------ | ---------- | ---------- |
| 1      | 2      | 3          | 4          |

## Parameters
- `category`: 教务处通知分类


## Features
- `antiCrawler`: true

## Radar
### Rule 1
- `source`:
  - `www.jwc.ynu.edu.cn/*`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 教务科 | 学籍科 | 教学研究科 | 实践科学科 |\n| ------ | ------ | ---------- | ---------- |\n| 1      | 2      | 3          | 4          |",
  "example": "/ynu/jwc/1",
  "features": {
    "antiCrawler": true
  },
  "heat": 0,
  "location": "jwc/zytz.ts",
  "maintainers": [
    "hzcheney"
  ],
  "name": "教务处主要通知",
  "parameters": {
    "category": "教务处通知分类"
  },
  "path": "/jwc/:category",
  "radar": [
    {
      "source": [
        "www.jwc.ynu.edu.cn/*"
      ]
    }
  ],
  "topFeeds": []
}
```
