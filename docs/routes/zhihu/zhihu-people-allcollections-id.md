# 知乎 - 用户全部收藏内容

## Coverage
`index-only`

## Route
- Namespace: `zhihu`
- Namespace Name: `知乎`
- Route Path: `/zhihu/people/allCollections/:id`
- Route Name: `用户全部收藏内容`
- Example: `/zhihu/people/allCollections/87-44-49-67`
- URL: `www.zhihu.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `Healthyyue`
- Source Location: `all-collections.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 作者 id，可在用户主页 URL 中找到


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
  - `www.zhihu.com/people/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/zhihu/people/allCollections/87-44-49-67",
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
  "heat": 7,
  "location": "all-collections.ts",
  "maintainers": [
    "Healthyyue"
  ],
  "name": "用户全部收藏内容",
  "parameters": {
    "id": "作者 id，可在用户主页 URL 中找到"
  },
  "path": "/people/allCollections/:id",
  "radar": [
    {
      "source": [
        "www.zhihu.com/people/:id"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": "轻调的知乎收藏 - Powered by RSSHub",
      "errorAt": "2025-04-18T10:05:08.595Z",
      "errorMessage": "[GET] \"https://api.zhihu.com/people/87-44-49-67/collections\": 401 Authorization Required\n",
      "id": "100718525432653824",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.zhihu.com/people/87-44-49-67/collections",
      "title": "轻调的知乎收藏",
      "type": "feed",
      "url": "rsshub://zhihu/people/allCollections/87-44-49-67"
    },
    {
      "description": "浅梦的知乎收藏 - Powered by RSSHub",
      "errorAt": "2025-04-22T12:14:00.216Z",
      "errorMessage": "[GET] \"https://api.zhihu.com/people/shenweichen/collections\": 401 Authorization Required\n",
      "id": "108334119878358016",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.zhihu.com/people/shenweichen/collections",
      "title": "浅梦的知乎收藏",
      "type": "feed",
      "url": "rsshub://zhihu/people/allCollections/shenweichen"
    }
  ],
  "view": 0
}
```
