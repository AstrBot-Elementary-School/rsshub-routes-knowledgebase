# 北京林业大学 - 信息学院通知

## Coverage
`index-only`

## Route
- Namespace: `bjfu`
- Namespace Name: `北京林业大学`
- Route Path: `/bjfu/it/:type`
- Route Name: `信息学院通知`
- Example: `/bjfu/it/xyxw`
- URL: `graduate.bjfu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `wzc-blog`
- Source Location: `it/index.ts`
- Source Module: `_None_`

## Description
| 学院新闻 | 科研动态 | 本科生培养 | 研究生培养 |
| -------- | -------- | ---------- | ---------- |
| xyxw     | kydt     | pydt       | pydt2      |

## Parameters
- `type`: 通知类别


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
  - `it.bjfu.edu.cn/:type/index.html`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 学院新闻 | 科研动态 | 本科生培养 | 研究生培养 |\n| -------- | -------- | ---------- | ---------- |\n| xyxw     | kydt     | pydt       | pydt2      |",
  "example": "/bjfu/it/xyxw",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "it/index.ts",
  "maintainers": [
    "wzc-blog"
  ],
  "name": "信息学院通知",
  "parameters": {
    "type": "通知类别"
  },
  "path": "/it/:type",
  "radar": [
    {
      "source": [
        "it.bjfu.edu.cn/:type/index.html"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
