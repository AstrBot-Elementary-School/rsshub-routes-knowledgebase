# 前瞻网 - 文章列表

## Coverage
`index-only`

## Route
- Namespace: `qianzhan`
- Namespace Name: `前瞻网`
- Route Path: `/qianzhan/analyst/column/:type?`
- Route Name: `文章列表`
- Example: `/qianzhan/analyst/column/all`
- URL: `qianzhan.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `moke8`
- Source Location: `column.ts`
- Source Module: `_None_`

## Description
| 全部 | 研究员专栏 | 规划师专栏 | 观察家专栏 |
| ---- | ---------- | ---------- | ---------- |
| all  | 220        | 627        | 329        |

## Parameters
- `type`: 分类，见下表


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
    "finance"
  ],
  "description": "| 全部 | 研究员专栏 | 规划师专栏 | 观察家专栏 |\n| ---- | ---------- | ---------- | ---------- |\n| all  | 220        | 627        | 329        |",
  "example": "/qianzhan/analyst/column/all",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 50,
  "location": "column.ts",
  "maintainers": [
    "moke8"
  ],
  "name": "文章列表",
  "parameters": {
    "type": "分类，见下表"
  },
  "path": "/analyst/column/:type?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "前瞻经济学人 - 最新文章 - Powered by RSSHub",
      "errorAt": "2026-09-01T08:03:28.782Z",
      "errorMessage": "Failed to fetch\n",
      "id": "66758050974691328",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.qianzhan.com/analyst/",
      "title": "前瞻经济学人 - 最新文章",
      "type": "feed",
      "url": "rsshub://qianzhan/analyst/column/all"
    },
    {
      "description": "前瞻经济学人 - 最新文章 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "149540527549611008",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.qianzhan.com/analyst/",
      "title": "前瞻经济学人 - 最新文章",
      "type": "feed",
      "url": "rsshub://qianzhan/analyst/column"
    }
  ]
}
```
