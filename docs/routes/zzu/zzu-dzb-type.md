# 郑州大学 - 党政办

## Coverage
`index-only`

## Route
- Namespace: `zzu`
- Namespace Name: `郑州大学`
- Route Path: `/zzu/dzb/:type`
- Route Name: `党政办`
- Example: `/zzu/dzb/xwzx`
- URL: `www.zzu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `amandus1990`
- Source Location: `dzb.ts`
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
  - `www5.zzu.edu.cn/dzb/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 新闻资讯 | 通知公告 |\n| -------- | -------- |\n| xwzx     | tzgg     |",
  "example": "/zzu/dzb/xwzx",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "dzb.ts",
  "maintainers": [
    "amandus1990"
  ],
  "name": "党政办",
  "parameters": {
    "type": "分类名"
  },
  "path": "/dzb/:type",
  "radar": [
    {
      "source": [
        "www5.zzu.edu.cn/dzb/"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
