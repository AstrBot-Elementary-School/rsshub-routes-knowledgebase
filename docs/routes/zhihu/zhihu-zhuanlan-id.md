# 知乎 - 专栏

## Coverage
`index-only`

## Route
- Namespace: `zhihu`
- Namespace Name: `知乎`
- Route Path: `/zhihu/zhuanlan/:id`
- Route Name: `专栏`
- Example: `/zhihu/zhuanlan/googledevelopers`
- URL: `www.zhihu.com`
- Language: `_None_`
- Categories: `social-media, popular`
- Maintainers: `DIYgod`
- Source Location: `zhuanlan.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 专栏 id，可在专栏主页 URL 中找到


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
  - `zhuanlan.zhihu.com/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media",
    "popular"
  ],
  "example": "/zhihu/zhuanlan/googledevelopers",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1866,
  "location": "zhuanlan.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "专栏",
  "parameters": {
    "id": "专栏 id，可在专栏主页 URL 中找到"
  },
  "path": "/zhuanlan/:id",
  "radar": [
    {
      "source": [
        "zhuanlan.zhihu.com/:id"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "知乎专栏-体验碎周报 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41359836954400791",
      "image": "https://picx.zhimg.com/v2-f111d7ee1c41944859e975a712c0883b_720w.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.zhihu.com/column/c_1186819163765649408",
      "title": "知乎专栏-体验碎周报",
      "type": "feed",
      "url": "rsshub://zhihu/zhuanlan/c_1186819163765649408"
    },
    {
      "description": "知乎专栏-玉树芝兰 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "57215618626397184",
      "image": "https://picx.zhimg.com/v2-f111d7ee1c41944859e975a712c0883b_720w.jpg",
      "ownerUserId": null,
      "siteUrl": "https://zhuanlan.zhihu.com/yushuzhilan",
      "title": "知乎专栏-玉树芝兰",
      "type": "feed",
      "url": "rsshub://zhihu/zhuanlan/yushuzhilan"
    }
  ]
}
```
