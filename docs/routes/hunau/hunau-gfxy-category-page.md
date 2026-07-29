# 湖南农业大学 - 公共管理与法学学院

## Coverage
`index-only`

## Route
- Namespace: `hunau`
- Namespace Name: `湖南农业大学`
- Route Path: `/hunau/gfxy/:category?/:page?`
- Route Name: `公共管理与法学学院`
- Example: `/hunau/gfxy`
- URL: `xky.hunau.edu.cn/`
- Language: `_None_`
- Categories: `university`
- Maintainers: `lcandy2`
- Source Location: `gfxy/index.ts`
- Source Module: `_None_`

## Description
| 分类 | 通知公告 | 学院新闻 | 其他分类通知... |
| ---- | -------- | -------- | --------------- |
| 参数 | tzgg     | xyxw     | 对应 URL        |

## Parameters
- `category`: 页面分类，默认为 `tzgg`
- `page`: 页码，默认为 `1`


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
  - `xky.hunau.edu.cn/`
  - `xky.hunau.edu.cn/tzgg_8472`
  - `xky.hunau.edu.cn/:category`
- `target`: `/:category`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 分类 | 通知公告 | 学院新闻 | 其他分类通知... |\n| ---- | -------- | -------- | --------------- |\n| 参数 | tzgg     | xyxw     | 对应 URL        |",
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
    "category": "页面分类，默认为 `tzgg`",
    "page": "页码，默认为 `1`"
  },
  "path": "/gfxy/:category?/:page?",
  "radar": [
    {
      "source": [
        "xky.hunau.edu.cn/",
        "xky.hunau.edu.cn/tzgg_8472",
        "xky.hunau.edu.cn/:category"
      ],
      "target": "/:category"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [],
  "url": "xky.hunau.edu.cn/"
}
```
