# 郑州大学 - 资产与财务部

## Coverage
`index-only`

## Route
- Namespace: `zzu`
- Namespace Name: `郑州大学`
- Route Path: `/zzu/zcycwb/:type`
- Route Name: `资产与财务部`
- Example: `/zzu/zcycwb/xwzx`
- URL: `www.zzu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `amandus1990`
- Source Location: `zcycwb.ts`
- Source Module: `_None_`

## Description
| 新闻资讯 | 通知公告 |
| -------- | -------- |
| xwzx     | tzgg     |

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
  - `www5.zzu.edu.cn/zcycwb/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 新闻资讯 | 通知公告 |\n| -------- | -------- |\n| xwzx     | tzgg     |",
  "example": "/zzu/zcycwb/xwzx",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "zcycwb.ts",
  "maintainers": [
    "amandus1990"
  ],
  "name": "资产与财务部",
  "parameters": {
    "type": "分类名"
  },
  "path": "/zcycwb/:type",
  "radar": [
    {
      "source": [
        "www5.zzu.edu.cn/zcycwb/"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
