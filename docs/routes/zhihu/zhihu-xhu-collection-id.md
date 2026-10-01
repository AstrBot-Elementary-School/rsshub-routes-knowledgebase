# 知乎 - xhu - 收藏夹

## Coverage
`index-only`

## Route
- Namespace: `zhihu`
- Namespace Name: `知乎`
- Route Path: `/zhihu/xhu/collection/:id`
- Route Name: `xhu - 收藏夹`
- Example: `/zhihu/xhu/collection/26444956`
- URL: `www.zhihu.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `JimenezLi`
- Source Location: `xhu/collection.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 收藏夹 id, 可在收藏夹页面 URL 中找到


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
  - `www.zhihu.com/collection/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/zhihu/xhu/collection/26444956",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 32,
  "location": "xhu/collection.ts",
  "maintainers": [
    "JimenezLi"
  ],
  "name": "xhu - 收藏夹",
  "parameters": {
    "id": "收藏夹 id, 可在收藏夹页面 URL 中找到"
  },
  "path": "/xhu/collection/:id",
  "radar": [
    {
      "source": [
        "www.zhihu.com/collection/:id"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "没有星座，没有催眠，没有这是什么心理，没有郁闷，没有发狂，只有一些冷冰冰的干货 - Powered by RSSHub",
      "errorAt": "2025-07-11T09:02:50.544Z",
      "errorMessage": "[GET] \"https://api.zhihuvvv.workers.dev/appcloud/v1/device\": <no response> fetch failed\n[GET] \"https://api.zhihuvvv.workers.dev/guests/token\": 401 Unauthorized\n",
      "id": "75086959921015808",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.zhihu.com/collection/19706511",
      "title": "知乎收藏夹-心理学与精神病学",
      "type": "feed",
      "url": "rsshub://zhihu/xhu/collection/19706511"
    },
    {
      "description": "dsbfknbsaknld - Powered by RSSHub",
      "errorAt": "2025-03-27T08:12:29.508Z",
      "errorMessage": "[GET] \"https://api.zhihuvvv.workers.dev/appcloud/v1/device\": <no response> fetch failed\n[GET] \"https://api.zhihuvvv.workers.dev/guests/token\": 401 Unauthorized\n",
      "id": "60609119526982656",
      "image": null,
      "ownerUserId": "60153739071642624",
      "siteUrl": "https://www.zhihu.com/collection/966804523",
      "title": "知乎收藏夹-test",
      "type": "feed",
      "url": "rsshub://zhihu/xhu/collection/966804523"
    }
  ]
}
```
