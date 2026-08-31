# 36kr - 资讯热榜

## Coverage
`index-only`

## Route
- Namespace: `36kr`
- Namespace Name: `36kr`
- Route Path: `/36kr/hot-list/:category?`
- Route Name: `资讯热榜`
- Example: `/36kr/hot-list`
- URL: `36kr.com`
- Language: `_None_`
- Categories: `new-media, popular`
- Maintainers: `nczitzk`
- Source Location: `hot-list.ts`
- Source Module: `_None_`

## Description
| 24 小时热榜 | 资讯人气榜 | 资讯综合榜 | 资讯收藏榜 |
| ----------- | ---------- | ---------- | ---------- |
| 24          | renqi      | zonghe     | shoucang   |

## Parameters
- `category`: 分类，默认为24小时热榜


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
  - `36kr.com/hot-list/:category`
  - `36kr.com/`
- `target`: `/hot-list/:category`

## Raw JSON
```json
{
  "categories": [
    "new-media",
    "popular"
  ],
  "description": "| 24 小时热榜 | 资讯人气榜 | 资讯综合榜 | 资讯收藏榜 |\n| ----------- | ---------- | ---------- | ---------- |\n| 24          | renqi      | zonghe     | shoucang   |",
  "example": "/36kr/hot-list",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 18554,
  "location": "hot-list.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "资讯热榜",
  "parameters": {
    "category": "分类，默认为24小时热榜"
  },
  "path": "/hot-list/:category?",
  "radar": [
    {
      "source": [
        "36kr.com/hot-list/:category",
        "36kr.com/"
      ],
      "target": "/hot-list/:category"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "36氪 - 24小时热榜 - Powered by RSSHub",
      "errorAt": "2026-08-24T01:58:48.508Z",
      "errorMessage": "200 ",
      "id": "41489882518602759",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.36kr.com/",
      "title": "36氪 - 24小时热榜",
      "type": "feed",
      "url": "rsshub://36kr/hot-list"
    },
    {
      "description": "36氪 - 24小时热榜 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "66137240013092864",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.36kr.com/",
      "title": "36氪 - 24小时热榜",
      "type": "feed",
      "url": "rsshub://36kr/hot-list/24"
    }
  ]
}
```
