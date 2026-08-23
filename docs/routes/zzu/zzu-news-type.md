# 郑州大学 - 郑大新闻网

## Coverage
`index-only`

## Route
- Namespace: `zzu`
- Namespace Name: `郑州大学`
- Route Path: `/zzu/news/:type`
- Route Name: `郑大新闻网`
- Example: `/zzu/news/ywsd`
- URL: `www.zzu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `nia3y, amandus1990`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| 要闻速递 | 教学科研 | 基层动态 | 媒体郑大 |
| -------- | -------- | -------- | -------- |
| ywsd     | jxky     | jcdt     | mtzd     |

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
  - `news.zzu.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 要闻速递 | 教学科研 | 基层动态 | 媒体郑大 |\n| -------- | -------- | -------- | -------- |\n| ywsd     | jxky     | jcdt     | mtzd     |",
  "example": "/zzu/news/ywsd",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "nia3y",
    "amandus1990"
  ],
  "name": "郑大新闻网",
  "parameters": {
    "type": "分类名"
  },
  "path": "/news/:type",
  "radar": [
    {
      "source": [
        "news.zzu.edu.cn/"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
