# 安徽农业大学 - 人工智能学院

## Coverage
`index-only`

## Route
- Namespace: `ahau`
- Namespace Name: `安徽农业大学`
- Route Path: `/ahau/cs_news/:type`
- Route Name: `人工智能学院`
- Example: `/ahau/cs_news/tzgg`
- URL: `xzxy.ahau.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `SimonHu-HN`
- Source Location: `cs-news.ts`
- Source Module: `_None_`

## Description
| 学院要闻 | 通知公告 |
| -------- | -------- |
| xyyw     | tzgg     |

## Parameters
- `type`: 类型名


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `xzxy.ahau.edu.cn/index/:type.htm`
- `target`: `/cs_news/:type`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 学院要闻 | 通知公告 |\n| -------- | -------- |\n| xyyw     | tzgg     |",
  "example": "/ahau/cs_news/tzgg",
  "heat": 0,
  "location": "cs-news.ts",
  "maintainers": [
    "SimonHu-HN"
  ],
  "name": "人工智能学院",
  "parameters": {
    "type": "类型名"
  },
  "path": "/cs_news/:type",
  "radar": [
    {
      "source": [
        "xzxy.ahau.edu.cn/index/:type.htm"
      ],
      "target": "/cs_news/:type"
    }
  ],
  "topFeeds": [],
  "url": "xzxy.ahau.edu.cn"
}
```
