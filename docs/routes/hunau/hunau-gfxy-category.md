# 湖南农业大学 - 公共管理与法学学院

## Coverage
`index-only`

## Route
- Namespace: `hunau`
- Namespace Name: `湖南农业大学`
- Route Path: `/hunau/gfxy/:category?`
- Route Name: `公共管理与法学学院`
- Example: `/hunau/gfxy`
- URL: `gfxy.hunau.edu.cn/`
- Language: `_None_`
- Categories: `university`
- Maintainers: `lcandy2`
- Source Location: `gfxy/index.ts`
- Source Module: `_None_`

## Description
| 分类 | 通知公告 | 学院要闻 | 其他分类通知... |
| ---- | -------- | -------- | --------------- |
| 参数 | tzgg     | xyyw     | 对应 URL        |

## Parameters
- `category`: 页面分类，默认为 `tzgg`


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
  - `gfxy.hunau.edu.cn/`
- `target`: `/gfxy`
### Rule 2
- `source`:
  - `gfxy.hunau.edu.cn/tzgg_0`
  - `gfxy.hunau.edu.cn/tzgg_0/index.html`
- `target`: `/gfxy`
### Rule 3
- `source`:
  - `gfxy.hunau.edu.cn/xyyw`
  - `gfxy.hunau.edu.cn/xyyw/index.html`
- `target`: `/gfxy/xyyw`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 分类 | 通知公告 | 学院要闻 | 其他分类通知... |\n| ---- | -------- | -------- | --------------- |\n| 参数 | tzgg     | xyyw     | 对应 URL        |",
  "example": "/hunau/gfxy",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "gfxy/index.ts",
  "maintainers": [
    "lcandy2"
  ],
  "name": "公共管理与法学学院",
  "parameters": {
    "category": "页面分类，默认为 `tzgg`"
  },
  "path": "/gfxy/:category?",
  "radar": [
    {
      "source": [
        "gfxy.hunau.edu.cn/"
      ],
      "target": "/gfxy"
    },
    {
      "source": [
        "gfxy.hunau.edu.cn/tzgg_0",
        "gfxy.hunau.edu.cn/tzgg_0/index.html"
      ],
      "target": "/gfxy"
    },
    {
      "source": [
        "gfxy.hunau.edu.cn/xyyw",
        "gfxy.hunau.edu.cn/xyyw/index.html"
      ],
      "target": "/gfxy/xyyw"
    }
  ],
  "topFeeds": [],
  "url": "gfxy.hunau.edu.cn/"
}
```
