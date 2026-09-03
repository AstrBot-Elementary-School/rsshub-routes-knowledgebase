# 简书 - 专题

## Coverage
`index-only`

## Route
- Namespace: `jianshu`
- Namespace Name: `简书`
- Route Path: `/jianshu/collection/:id`
- Route Name: `专题`
- Example: `/jianshu/collection/xYuZYD`
- URL: `www.jianshu.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `DIYgod, HenryQW, JimenezLi`
- Source Location: `collection.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 专题 id, 可在专题页 URL 中找到


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
  - `www.jianshu.com/c/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/jianshu/collection/xYuZYD",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 112,
  "location": "collection.ts",
  "maintainers": [
    "DIYgod",
    "HenryQW",
    "JimenezLi"
  ],
  "name": "专题",
  "parameters": {
    "id": "专题 id, 可在专题页 URL 中找到"
  },
  "path": "/collection/:id",
  "radar": [
    {
      "source": [
        "www.jianshu.com/c/:id"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "如果你是程序员，或者有一颗喜欢写程序的心，喜欢分享技术干货、项目经验、程序员日常囧事等等，欢迎投稿《程序员》专题。 专题主编：小彤花园 http://www.jianshu.com/users... - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "56631583574321152",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.jianshu.com/c/NEt52a",
      "title": "程序员 - 专题 - 简书",
      "type": "feed",
      "url": "rsshub://jianshu/collection/NEt52a"
    },
    {
      "description": "微服务和SOA相关的理论知识和技术知识，spring cloud，spring boot，dubbo，rpc，thrift，protobuf，gRPC，分布式事务，DDD,k8s,kuberne... - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "69647312270682129",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.jianshu.com/c/3f476518d832",
      "title": "微服务架构和实践 - 专题 - 简书",
      "type": "feed",
      "url": "rsshub://jianshu/collection/3f476518d832"
    }
  ],
  "view": 0
}
```
