# 扬州大学 - 研究生招生

## Coverage
`index-only`

## Route
- Namespace: `yzu`
- Namespace Name: `扬州大学`
- Route Path: `/yzu/yjszs/:type`
- Route Name: `研究生招生`
- Example: `/yzu/yjszs/tzgg`
- URL: `www.yzu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `LogicJake`
- Source Location: `yjszs.ts`
- Source Module: `_None_`

## Description
| 通知公告 | 博士研究生招生 | 硕士研究生招生 |
| -------- | -------------- | -------------- |
| tzgg     | bszs           | sszs           |

## Parameters
- `type`: 分类名


## Features
- `requirePuppeteer`: true
- `antiCrawler`: true

## Radar
### Rule 1
- `title`: `通知公告`
- `source`:
  - `yjszs.yzu.edu.cn/tzgg/tzgg.htm`
- `target`: `/yjszs/tzgg`
### Rule 2
- `title`: `博士研究生招生`
- `source`:
  - `yjszs.yzu.edu.cn/tzgg/bsyjszs.htm`
- `target`: `/yjszs/bszs`
### Rule 3
- `title`: `硕士研究生招生`
- `source`:
  - `yjszs.yzu.edu.cn/tzgg/ssyjszs.htm`
- `target`: `/yjszs/sszs`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 通知公告 | 博士研究生招生 | 硕士研究生招生 |\n| -------- | -------------- | -------------- |\n| tzgg     | bszs           | sszs           |",
  "example": "/yzu/yjszs/tzgg",
  "features": {
    "antiCrawler": true,
    "requirePuppeteer": true
  },
  "heat": 0,
  "location": "yjszs.ts",
  "maintainers": [
    "LogicJake"
  ],
  "name": "研究生招生",
  "parameters": {
    "type": "分类名"
  },
  "path": "/yjszs/:type",
  "radar": [
    {
      "source": [
        "yjszs.yzu.edu.cn/tzgg/tzgg.htm"
      ],
      "target": "/yjszs/tzgg",
      "title": "通知公告"
    },
    {
      "source": [
        "yjszs.yzu.edu.cn/tzgg/bsyjszs.htm"
      ],
      "target": "/yjszs/bszs",
      "title": "博士研究生招生"
    },
    {
      "source": [
        "yjszs.yzu.edu.cn/tzgg/ssyjszs.htm"
      ],
      "target": "/yjszs/sszs",
      "title": "硕士研究生招生"
    }
  ],
  "topFeeds": []
}
```
