# 郑州大学 - 党委宣传部

## Coverage
`index-only`

## Route
- Namespace: `zzu`
- Namespace Name: `郑州大学`
- Route Path: `/zzu/xuan/:type`
- Route Name: `党委宣传部`
- Example: `/zzu/xuan/gzdt`
- URL: `www.zzu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `amandus1990`
- Source Location: `xuan.ts`
- Source Module: `_None_`

## Description
| 工作动态 | 通知公告 |
| -------- | -------- |
| gzdt     | tzgg     |

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
  - `www5.zzu.edu.cn/xuan/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 工作动态 | 通知公告 |\n| -------- | -------- |\n| gzdt     | tzgg     |",
  "example": "/zzu/xuan/gzdt",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "xuan.ts",
  "maintainers": [
    "amandus1990"
  ],
  "name": "党委宣传部",
  "parameters": {
    "type": "分类名"
  },
  "path": "/xuan/:type",
  "radar": [
    {
      "source": [
        "www5.zzu.edu.cn/xuan/"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
