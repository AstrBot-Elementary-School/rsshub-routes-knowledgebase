# 中国海洋大学 - 信息科学与工程学院团学工作

## Coverage
`index-only`

## Route
- Namespace: `ouc`
- Namespace Name: `中国海洋大学`
- Route Path: `/ouc/it/tx/:id?`
- Route Name: `信息科学与工程学院团学工作`
- Example: `/ouc/it/tx/xwdt`
- URL: `it.ouc.edu.cn/`
- Language: `_None_`
- Categories: `university`
- Maintainers: `3401797899`
- Source Location: `it-tx.ts`
- Source Module: `_None_`

## Description
| 新闻动态 | 学院活动 | 奖助工作获奖情况 |
| -------- | -------- | ---------------- |
| xwdt     | tzgg     | 21758            |

## Parameters
- `id`: 默认为 `xwdt`，id过多，这里只举几个例


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `it.ouc.edu.cn/tx/:id/list.htm`
- `target`: `/it/tx/:id`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 新闻动态 | 学院活动 | 奖助工作获奖情况 |\n| -------- | -------- | ---------------- |\n| xwdt     | tzgg     | 21758            |",
  "example": "/ouc/it/tx/xwdt",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "it-tx.ts",
  "maintainers": [
    "3401797899"
  ],
  "name": "信息科学与工程学院团学工作",
  "parameters": {
    "id": "默认为 `xwdt`，id过多，这里只举几个例"
  },
  "path": "/it/tx/:id?",
  "radar": [
    {
      "source": [
        "it.ouc.edu.cn/tx/:id/list.htm"
      ],
      "target": "/it/tx/:id"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "it.ouc.edu.cn/"
}
```
