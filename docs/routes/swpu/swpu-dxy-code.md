# 西南石油大学 - 电气信息学院

## Coverage
`index-only`

## Route
- Namespace: `swpu`
- Namespace Name: `西南石油大学`
- Route Path: `/swpu/dxy/:code`
- Route Name: `电气信息学院`
- Example: `/swpu/dxy/1156`
- URL: `swpu.edu.cn/`
- Language: `_None_`
- Categories: `university`
- Maintainers: `CYTMWIA`
- Source Location: `dxy.ts`
- Source Module: `_None_`

## Description
| 栏目 | 学院新闻 | 学院通知 |
| ---- | -------- | -------- |
| 代码 | 1122     | 1156     |

## Parameters
- `code`: 栏目代码


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
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
  "description": "| 栏目 | 学院新闻 | 学院通知 |\n| ---- | -------- | -------- |\n| 代码 | 1122     | 1156     |",
  "example": "/swpu/dxy/1156",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "dxy.ts",
  "maintainers": [
    "CYTMWIA"
  ],
  "name": "电气信息学院",
  "parameters": {
    "code": "栏目代码"
  },
  "path": "/dxy/:code",
  "radar": [
    {
      "source": [
        "swpu.edu.cn/"
      ],
      "target": ""
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [],
  "url": "swpu.edu.cn/"
}
```
