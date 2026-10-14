# 湖南农业大学 - 信息与智能科学技术学院

## Coverage
`index-only`

## Route
- Namespace: `hunau`
- Namespace Name: `湖南农业大学`
- Route Path: `/hunau/xky/:category?`
- Route Name: `信息与智能科学技术学院`
- Example: `/hunau/xky`
- URL: `xky.hunau.edu.cn/`
- Language: `_None_`
- Categories: `university`
- Maintainers: `lcandy2`
- Source Location: `xky/index.ts`
- Source Module: `_None_`

## Description
| 分类 | 通知公告   | 学院新闻 | 其他分类通知... |
| ---- | ---------- | -------- | --------------- |
| 参数 | tzgg\_8472 | xyxw     | 对应 URL        |

## Parameters
- `category`: 页面分类，默认为 `tzgg_8472`


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
- `target`: `/xky`
### Rule 2
- `source`:
  - `xky.hunau.edu.cn/tzgg_8472`
  - `xky.hunau.edu.cn/tzgg_8472/index.html`
- `target`: `/xky`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 分类 | 通知公告   | 学院新闻 | 其他分类通知... |\n| ---- | ---------- | -------- | --------------- |\n| 参数 | tzgg\\_8472 | xyxw     | 对应 URL        |",
  "example": "/hunau/xky",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "xky/index.ts",
  "maintainers": [
    "lcandy2"
  ],
  "name": "信息与智能科学技术学院",
  "parameters": {
    "category": "页面分类，默认为 `tzgg_8472`"
  },
  "path": "/xky/:category?",
  "radar": [
    {
      "source": [
        "xky.hunau.edu.cn/"
      ],
      "target": "/xky"
    },
    {
      "source": [
        "xky.hunau.edu.cn/tzgg_8472",
        "xky.hunau.edu.cn/tzgg_8472/index.html"
      ],
      "target": "/xky"
    }
  ],
  "topFeeds": [],
  "url": "xky.hunau.edu.cn/"
}
```
