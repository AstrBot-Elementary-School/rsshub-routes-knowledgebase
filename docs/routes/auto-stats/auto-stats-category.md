# 中国汽车工业协会统计信息网 - 分类

## Coverage
`index-only`

## Route
- Namespace: `auto-stats`
- Namespace Name: `中国汽车工业协会统计信息网`
- Route Path: `/auto-stats/:category?`
- Route Name: `分类`
- Example: `/auto-stats`
- URL: `auto-stats.org.cn`
- Language: `_None_`
- Categories: `other`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 信息快递 | 工作动态 | 专题分析 |
| -------- | -------- | -------- |
| xxkd     | gzdt     | ztfx     |

## Parameters
- `category`: 分类，见下表，默认为信息快递


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "| 信息快递 | 工作动态 | 专题分析 |\n| -------- | -------- | -------- |\n| xxkd     | gzdt     | ztfx     |",
  "example": "/auto-stats",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "分类",
  "parameters": {
    "category": "分类，见下表，默认为信息快递"
  },
  "path": "/:category?",
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
