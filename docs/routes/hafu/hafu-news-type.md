# 河南财政金融学院 - 河南财政金融学院

## Coverage
`index-only`

## Route
- Namespace: `hafu`
- Namespace Name: `河南财政金融学院`
- Route Path: `/hafu/news/:type?`
- Route Name: `河南财政金融学院`
- Example: `/hafu/news/ggtz`
- URL: `www.hafu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `deep1nlife`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| 校内公告通知 | 教务处公告通知 | 招生就业处公告通知 |
| ------------ | -------------- | ------------------ |
| ggtz         | jwc            | zsjyc              |

## Parameters
- `type`: 分类，见下表（默认为 `ggtz`)


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 校内公告通知 | 教务处公告通知 | 招生就业处公告通知 |\n| ------------ | -------------- | ------------------ |\n| ggtz         | jwc            | zsjyc              |",
  "example": "/hafu/news/ggtz",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "deep1nlife"
  ],
  "name": "河南财政金融学院",
  "parameters": {
    "type": "分类，见下表（默认为 `ggtz`)"
  },
  "path": "/news/:type?",
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
