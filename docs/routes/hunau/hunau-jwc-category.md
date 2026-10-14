# 湖南农业大学 - 教务处

## Coverage
`index-only`

## Route
- Namespace: `hunau`
- Namespace Name: `湖南农业大学`
- Route Path: `/hunau/jwc/:category?`
- Route Name: `教务处`
- Example: `/hunau/jwc`
- URL: `jwc.hunau.edu.cn/`
- Language: `_None_`
- Categories: `university`
- Maintainers: `lcandy2`
- Source Location: `jwc.ts`
- Source Module: `_None_`

## Description
| 分类 | 通知公告 | 教务动态 | 其他教务通知... |
| ---- | -------- | -------- | --------------- |
| 参数 | tzgg     | jwdt     | 对应 URL        |

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
  - `jwc.hunau.edu.cn/`
- `target`: `/jwc`
### Rule 2
- `source`:
  - `jwc.hunau.edu.cn/tzgg`
  - `jwc.hunau.edu.cn/tzgg/index.html`
- `target`: `/jwc`
### Rule 3
- `source`:
  - `jwc.hunau.edu.cn/jwdt`
  - `jwc.hunau.edu.cn/jwdt/index.html`
- `target`: `/jwc/jwdt`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 分类 | 通知公告 | 教务动态 | 其他教务通知... |\n| ---- | -------- | -------- | --------------- |\n| 参数 | tzgg     | jwdt     | 对应 URL        |",
  "example": "/hunau/jwc",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "jwc.ts",
  "maintainers": [
    "lcandy2"
  ],
  "name": "教务处",
  "parameters": {
    "category": "页面分类，默认为 `tzgg`"
  },
  "path": "/jwc/:category?",
  "radar": [
    {
      "source": [
        "jwc.hunau.edu.cn/"
      ],
      "target": "/jwc"
    },
    {
      "source": [
        "jwc.hunau.edu.cn/tzgg",
        "jwc.hunau.edu.cn/tzgg/index.html"
      ],
      "target": "/jwc"
    },
    {
      "source": [
        "jwc.hunau.edu.cn/jwdt",
        "jwc.hunau.edu.cn/jwdt/index.html"
      ],
      "target": "/jwc/jwdt"
    }
  ],
  "topFeeds": [],
  "url": "jwc.hunau.edu.cn/"
}
```
