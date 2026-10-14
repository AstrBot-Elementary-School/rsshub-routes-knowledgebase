# 郑州大学 - 党委统战部

## Coverage
`index-only`

## Route
- Namespace: `zzu`
- Namespace Name: `郑州大学`
- Route Path: `/zzu/tzhb/:type`
- Route Name: `党委统战部`
- Example: `/zzu/tzhb/gzdt`
- URL: `www.zzu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `amandus1990`
- Source Location: `tzhb.ts`
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
  - `www5.zzu.edu.cn/tzhb/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 工作动态 | 通知公告 |\n| -------- | -------- |\n| gzdt     | tzgg     |",
  "example": "/zzu/tzhb/gzdt",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "tzhb.ts",
  "maintainers": [
    "amandus1990"
  ],
  "name": "党委统战部",
  "parameters": {
    "type": "分类名"
  },
  "path": "/tzhb/:type",
  "radar": [
    {
      "source": [
        "www5.zzu.edu.cn/tzhb/"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
