# 西南石油大学 - 财经学院

## Coverage
`index-only`

## Route
- Namespace: `swpu`
- Namespace Name: `西南石油大学`
- Route Path: `/swpu/cjxy/:code`
- Route Name: `财经学院`
- Example: `/swpu/cjxy/xyxw`
- URL: `swpu.edu.cn/`
- Language: `_None_`
- Categories: `university`
- Maintainers: `RiverTwilight`
- Source Location: `cjxy.ts`
- Source Module: `_None_`

## Description
| 栏目 | 学院新闻 | 学院通知 |
| ---- | -------- | -------- |
| 代码 | xyxw     | xytz     |

## Parameters
- `code`: 栏目代码


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
  - `swpu.edu.cn/`
- `target`: ``

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 栏目 | 学院新闻 | 学院通知 |\n| ---- | -------- | -------- |\n| 代码 | xyxw     | xytz     |",
  "example": "/swpu/cjxy/xyxw",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "cjxy.ts",
  "maintainers": [
    "RiverTwilight"
  ],
  "name": "财经学院",
  "parameters": {
    "code": "栏目代码"
  },
  "path": "/cjxy/:code",
  "radar": [
    {
      "source": [
        "swpu.edu.cn/"
      ],
      "target": ""
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "swpu.edu.cn/"
}
```
