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
- `requireConfig`: [{"description": "", "name": "ZHIHU_COOKIES"}]
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
  "heat": 1876,
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
  "topFeeds": [
    {
      "description": "知乎专栏-体验碎周报 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41359836954400791",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.zhihu.com/column/c_1186819163765649408",
      "title": "知乎专栏-体验碎周报",
      "type": "feed",
      "url": "rsshub://zhihu/zhuanlan/c_1186819163765649408"
    },
    {
      "description": "知乎专栏-玉树芝兰 - Powered by RSSHub",
      "errorAt": "2025-10-29T05:43:58.029Z",
      "errorMessage": "Cannot read properties of undefined (reading 'substring')\nCannot read properties of undefined (reading 'substring')\n",
      "id": "57215618626397184",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://zhuanlan.zhihu.com/yushuzhilan",
      "title": "知乎专栏-玉树芝兰",
      "type": "feed",
      "url": "rsshub://zhihu/zhuanlan/yushuzhilan"
    }
  ]
}
```
