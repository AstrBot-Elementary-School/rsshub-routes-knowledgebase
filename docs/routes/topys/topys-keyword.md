# TOPYS - 关键字

## Coverage
`index-only`

## Route
- Namespace: `topys`
- Namespace Name: `TOPYS`
- Route Path: `/topys/:keyword?`
- Route Name: `关键字`
- Example: `/topys`
- URL: `topys.cn`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 创意 | 设计 | 商业 | 艺术 | 文化 | 科技 |
| ---- | ---- | ---- | ---- | ---- | ---- |

## Parameters
- `keyword`: 关键字，可在对应结果页的 URL 中找到


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
  - `topys.cn/search/:keyword`
  - `topys.cn/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 创意 | 设计 | 商业 | 艺术 | 文化 | 科技 |\n| ---- | ---- | ---- | ---- | ---- | ---- |",
  "example": "/topys",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 337,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "关键字",
  "parameters": {
    "keyword": "关键字，可在对应结果页的 URL 中找到"
  },
  "path": "/:keyword?",
  "radar": [
    {
      "source": [
        "topys.cn/search/:keyword",
        "topys.cn/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "TOPYS - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "55870828931624960",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.topys.cn/pick",
      "title": "TOPYS",
      "type": "feed",
      "url": "rsshub://topys"
    },
    {
      "description": "设计 - TOPYS - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41489882518602753",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.topys.cn/search/%E8%AE%BE%E8%AE%A1",
      "title": "设计 - TOPYS",
      "type": "feed",
      "url": "rsshub://topys/%E8%AE%BE%E8%AE%A1"
    }
  ]
}
```
