# 郑州大学 - 教务部

## Coverage
`index-only`

## Route
- Namespace: `zzu`
- Namespace Name: `郑州大学`
- Route Path: `/zzu/jwc/:type`
- Route Name: `教务部`
- Example: `/zzu/jwc/xwkd`
- URL: `www.zzu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `amandus1990`
- Source Location: `jwc.ts`
- Source Module: `_None_`

## Description
| 新闻快递 | 通知公告 |
| -------- | -------- |
| xwkd     | tzgg     |

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
  - `www5.zzu.edu.cn/jwc/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 新闻快递 | 通知公告 |\n| -------- | -------- |\n| xwkd     | tzgg     |",
  "example": "/zzu/jwc/xwkd",
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
    "amandus1990"
  ],
  "name": "教务部",
  "parameters": {
    "type": "分类名"
  },
  "path": "/jwc/:type",
  "radar": [
    {
      "source": [
        "www5.zzu.edu.cn/jwc/"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
