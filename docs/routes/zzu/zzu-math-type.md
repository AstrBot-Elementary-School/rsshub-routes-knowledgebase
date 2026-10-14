# 郑州大学 - 数学与统计学院

## Coverage
`index-only`

## Route
- Namespace: `zzu`
- Namespace Name: `郑州大学`
- Route Path: `/zzu/math/:type`
- Route Name: `数学与统计学院`
- Example: `/zzu/math/xyxw`
- URL: `www.zzu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `amandus1990`
- Source Location: `math.ts`
- Source Module: `_None_`

## Description
| 学院新闻 | 通知公告 | 党工团学 | 学术报告 |
| -------- | -------- | -------- | -------- |
| xyxw     | tzgg     | dgtx     | xsbg     |

## Parameters
- `type`: 分类名


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www5.zzu.edu.cn/math/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 学院新闻 | 通知公告 | 党工团学 | 学术报告 |\n| -------- | -------- | -------- | -------- |\n| xyxw     | tzgg     | dgtx     | xsbg     |",
  "example": "/zzu/math/xyxw",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "math.ts",
  "maintainers": [
    "amandus1990"
  ],
  "name": "数学与统计学院",
  "parameters": {
    "type": "分类名"
  },
  "path": "/math/:type",
  "radar": [
    {
      "source": [
        "www5.zzu.edu.cn/math/"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
