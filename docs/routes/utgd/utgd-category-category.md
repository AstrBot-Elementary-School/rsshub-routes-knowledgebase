# UNTAG - 分类

## Coverage
`index-only`

## Route
- Namespace: `utgd`
- Namespace Name: `UNTAG`
- Route Path: `/utgd/category/:category?`
- Route Name: `分类`
- Example: `/utgd/category/method`
- URL: `utgd.net`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `category.ts`
- Source Module: `_None_`

## Description
| 方法   | 观点    |
| ------ | ------- |
| method | opinion |

## Parameters
- `category`: 分类，可在对应分类页的 URL 中找到，默认为方法


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
  - `utgd.net/category/s/:category`
  - `utgd.net/`
- `target`: `/category/:category`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 方法   | 观点    |\n| ------ | ------- |\n| method | opinion |",
  "example": "/utgd/category/method",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 29,
  "location": "category.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "分类",
  "parameters": {
    "category": "分类，可在对应分类页的 URL 中找到，默认为方法"
  },
  "path": "/category/:category?",
  "radar": [
    {
      "source": [
        "utgd.net/category/s/:category",
        "utgd.net/"
      ],
      "target": "/category/:category"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "来自本站作者们的方法型文章。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "84476443744540672",
      "image": "https://cdn.utgd.net",
      "ownerUserId": null,
      "siteUrl": "https://utgd.net/category/s/method",
      "title": "UNTAG - 方法",
      "type": "feed",
      "url": "rsshub://utgd/category"
    },
    {
      "description": "来自本站作者们的方法型文章。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "84874523594988544",
      "image": "https://cdn.utgd.net",
      "ownerUserId": null,
      "siteUrl": "https://utgd.net/category/s/method",
      "title": "UNTAG - 方法",
      "type": "feed",
      "url": "rsshub://utgd/category/method"
    }
  ]
}
```
