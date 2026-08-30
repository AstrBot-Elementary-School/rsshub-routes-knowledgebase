# 知乎 - 收藏夹

## Coverage
`index-only`

## Route
- Namespace: `zhihu`
- Namespace Name: `知乎`
- Route Path: `/zhihu/collection/:id/:getAll?`
- Route Name: `收藏夹`
- Example: `/zhihu/collection/26444956`
- URL: `www.zhihu.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `huruji, Colin-XKL, Fatpandac`
- Source Location: `collection.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 收藏夹 id，可在收藏夹页面 URL 中找到
- `getAll`: 获取全部收藏内容，任意值为打开


## Features
- `requireConfig`: [{"description": "", "name": "ZHIHU_COOKIES"}]
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.zhihu.com/collection/:id`
- `target`: `/collection/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/zhihu/collection/26444956",
  "features": {
    "antiCrawler": true,
    "requireConfig": [
      {
        "description": "",
        "name": "ZHIHU_COOKIES"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 145,
  "location": "collection.ts",
  "maintainers": [
    "huruji",
    "Colin-XKL",
    "Fatpandac"
  ],
  "name": "收藏夹",
  "parameters": {
    "getAll": "获取全部收藏内容，任意值为打开",
    "id": "收藏夹 id，可在收藏夹页面 URL 中找到"
  },
  "path": "/collection/:id/:getAll?",
  "radar": [
    {
      "source": [
        "www.zhihu.com/collection/:id"
      ],
      "target": "/collection/:id"
    }
  ],
  "topFeeds": [
    {
      "description": "知乎关注人数TOP 3收藏夹之一，请在为收藏的万赞相关评论区 @莫博之，或者私信我答案地址链接。 - Powered by RSSHub",
      "errorAt": "2026-02-23T18:43:42.452Z",
      "errorMessage": "[GET] \"https://www.zhihu.com/api/v4/collections/37406996/items?offset=0&limit=20\": 401 Authorization Required\n[GET] \"https://www.zhihu.com/api/v4/collections/37406996/items?offset=0&limit=20\": 401 Authorization Required\n",
      "id": "104524498543254528",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.zhihu.com/collection/37406996",
      "title": "知乎 一万 斩！！ - 知乎收藏夹",
      "type": "feed",
      "url": "rsshub://zhihu/collection/37406996"
    },
    {
      "description": "神答案 - 知乎收藏夹 - Powered by RSSHub",
      "errorAt": "2026-02-23T21:19:55.857Z",
      "errorMessage": "[GET] \"https://www.zhihu.com/api/v4/collections/38411239/items?offset=0&limit=20\": 401 Authorization Required\n[GET] \"https://www.zhihu.com/api/v4/collections/38411239/items?offset=0&limit=20\": 401 Authorization Required\n",
      "id": "104525421052935168",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.zhihu.com/collection/38411239",
      "title": "神答案 - 知乎收藏夹",
      "type": "feed",
      "url": "rsshub://zhihu/collection/38411239"
    }
  ]
}
```
