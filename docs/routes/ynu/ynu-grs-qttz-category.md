# 云南大学 - 研究生院其他通知

## Coverage
`index-only`

## Route
- Namespace: `ynu`
- Namespace Name: `云南大学`
- Route Path: `/ynu/grs/qttz/:category`
- Route Name: `研究生院其他通知`
- Example: `/ynu/grs/qttz/2`
- URL: `www.ynu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `hzcheney`
- Source Location: `grs/qttz.ts`
- Source Module: `_None_`

## Description
| 招生工作 | 研究生培养 | 质量管理 | 学位工作 | 综合办公室 | 相关下载 |
| -------- | ---------- | -------- | -------- | ---------- | -------- |
| 1        | 2          | 3        | 4        | 5          | 6        |

## Parameters
- `category`: 研究生院通知分类


## Features
- `antiCrawler`: true

## Radar
### Rule 1
- `source`:
  - `grs.ynu.edu.cn/*`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 招生工作 | 研究生培养 | 质量管理 | 学位工作 | 综合办公室 | 相关下载 |\n| -------- | ---------- | -------- | -------- | ---------- | -------- |\n| 1        | 2          | 3        | 4        | 5          | 6        |",
  "example": "/ynu/grs/qttz/2",
  "features": {
    "antiCrawler": true
  },
  "heat": 0,
  "location": "grs/qttz.ts",
  "maintainers": [
    "hzcheney"
  ],
  "name": "研究生院其他通知",
  "parameters": {
    "category": "研究生院通知分类"
  },
  "path": "/grs/qttz/:category",
  "radar": [
    {
      "source": [
        "grs.ynu.edu.cn/*"
      ]
    }
  ],
  "topFeeds": []
}
```
