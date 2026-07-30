# 简书 - 作者

## Coverage
`index-only`

## Route
- Namespace: `jianshu`
- Namespace Name: `简书`
- Route Path: `/jianshu/user/:id`
- Route Name: `作者`
- Example: `/jianshu/user/yZq3ZV`
- URL: `www.jianshu.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `DIYgod, HenryQW, JimenezLi`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 作者 id, 可在作者主页 URL 中找到


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
  - `www.jianshu.com/u/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/jianshu/user/yZq3ZV",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 138,
  "location": "user.ts",
  "maintainers": [
    "DIYgod",
    "HenryQW",
    "JimenezLi"
  ],
  "name": "作者",
  "parameters": {
    "id": "作者 id, 可在作者主页 URL 中找到"
  },
  "path": "/user/:id",
  "radar": [
    {
      "source": [
        "www.jianshu.com/u/:id"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "这个世界流行离开，但我们却不擅长告别 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "75713109098394624",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.jianshu.com/u/facc8bb791bc",
      "title": "单细胞空间交响乐 - 简书",
      "type": "feed",
      "url": "rsshub://jianshu/user/facc8bb791bc"
    },
    {
      "description": "学好方法论，换遍工作都不怕，这里是邢小作的《产品方法论集散地》，一个专注于分享产品方法论的空间，却不仅仅是产品方法论 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "66008375993664512",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.jianshu.com/u/de02b0c77277",
      "title": "产品方法论集散地 - 简书",
      "type": "feed",
      "url": "rsshub://jianshu/user/de02b0c77277"
    }
  ],
  "view": 0
}
```
