# 郑州大学 - 校长办

## Coverage
`index-only`

## Route
- Namespace: `zzu`
- Namespace Name: `郑州大学`
- Route Path: `/zzu/xbx/:type`
- Route Name: `校长办`
- Example: `/zzu/xbx/xwzx`
- URL: `www.zzu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `amandus1990`
- Source Location: `xbx.ts`
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
  - `www5.zzu.edu.cn/xbx/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 新闻资讯 | 通知公告 |\n| -------- | -------- |\n| xwzx     | tzgg     |",
  "example": "/zzu/xbx/xwzx",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "xbx.ts",
  "maintainers": [
    "amandus1990"
  ],
  "name": "校长办",
  "parameters": {
    "type": "分类名"
  },
  "path": "/xbx/:type",
  "radar": [
    {
      "source": [
        "www5.zzu.edu.cn/xbx/"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
