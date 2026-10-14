# 郑州大学 - 科研院

## Coverage
`index-only`

## Route
- Namespace: `zzu`
- Namespace Name: `郑州大学`
- Route Path: `/zzu/kjc/:type`
- Route Name: `科研院`
- Example: `/zzu/kjc/xwzx`
- URL: `www.zzu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `amandus1990`
- Source Location: `kjc.ts`
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
  - `www7.zzu.edu.cn/kjc/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 新闻资讯 | 通知公告 |\n| -------- | -------- |\n| xwzx     | tzgg     |",
  "example": "/zzu/kjc/xwzx",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "kjc.ts",
  "maintainers": [
    "amandus1990"
  ],
  "name": "科研院",
  "parameters": {
    "type": "分类名"
  },
  "path": "/kjc/:type",
  "radar": [
    {
      "source": [
        "www7.zzu.edu.cn/kjc/"
      ]
    }
  ],
  "topFeeds": []
}
```
