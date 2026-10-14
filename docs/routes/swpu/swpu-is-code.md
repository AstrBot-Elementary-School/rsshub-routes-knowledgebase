# 西南石油大学 - 信息学院

## Coverage
`index-only`

## Route
- Namespace: `swpu`
- Namespace Name: `西南石油大学`
- Route Path: `/swpu/is/:code`
- Route Name: `信息学院`
- Example: `/swpu/is/xyxw`
- URL: `swpu.edu.cn/`
- Language: `_None_`
- Categories: `university`
- Maintainers: `RiverTwilight`
- Source Location: `is.ts`
- Source Module: `_None_`

## Description
| 栏目 | 学院新闻 | 通知公告 | 教育教学 | 学生工作 | 招生就业 |
| ---- | -------- | -------- | -------- | -------- | -------- |
| 代码 | xyxw     | tzgg     | jyjx     | xsgz     | zsjy     |

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
- `title`: `信息学院 - 学院新闻`
- `source`:
  - `www.swpu.edu.cn/is/xydt/xyxw.htm`
- `target`: `/is/xyxw`
### Rule 2
- `title`: `信息学院 - 通知公告`
- `source`:
  - `www.swpu.edu.cn/is/xydt/tzgg.htm`
- `target`: `/is/tzgg`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 栏目 | 学院新闻 | 通知公告 | 教育教学 | 学生工作 | 招生就业 |\n| ---- | -------- | -------- | -------- | -------- | -------- |\n| 代码 | xyxw     | tzgg     | jyjx     | xsgz     | zsjy     |",
  "example": "/swpu/is/xyxw",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "is.ts",
  "maintainers": [
    "RiverTwilight"
  ],
  "name": "信息学院",
  "parameters": {
    "code": "栏目代码"
  },
  "path": "/is/:code",
  "radar": [
    {
      "source": [
        "www.swpu.edu.cn/is/xydt/xyxw.htm"
      ],
      "target": "/is/xyxw",
      "title": "信息学院 - 学院新闻"
    },
    {
      "source": [
        "www.swpu.edu.cn/is/xydt/tzgg.htm"
      ],
      "target": "/is/tzgg",
      "title": "信息学院 - 通知公告"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [],
  "url": "swpu.edu.cn/"
}
```
