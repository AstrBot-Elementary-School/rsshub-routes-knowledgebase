# 哔哩哔哩 bilibili - UP 主频道的合集

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/bilibili/user/collection/:uid/:sid/:embed?/:sortReverse?/:page?`
- Route Name: `UP 主频道的合集`
- Example: `/bilibili/user/collection/245645656/529166`
- URL: `www.bilibili.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `shininome, cscnk52`
- Source Location: `user-collection.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `uid`: 用户 id, 可在 UP 主主页中找到
- `sid`: 合集 id, 可在合集页面的 URL 中找到
- `embed`: 默认为开启内嵌视频, 任意值为关闭
- `sortReverse`: 默认:默认排序 1:升序排序
- `page`: 页码, 默认1


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/bilibili/user/collection/245645656/529166",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 931,
  "location": "user-collection.ts",
  "maintainers": [
    "shininome",
    "cscnk52"
  ],
  "name": "UP 主频道的合集",
  "parameters": {
    "embed": "默认为开启内嵌视频, 任意值为关闭",
    "page": "页码, 默认1",
    "sid": "合集 id, 可在合集页面的 URL 中找到",
    "sortReverse": "默认:默认排序 1:升序排序",
    "uid": "用户 id, 可在 UP 主主页中找到"
  },
  "path": "/user/collection/:uid/:sid/:embed?/:sortReverse?/:page?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "IT咖啡馆 的 bilibili 合集 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59567779750919168",
      "image": "https://i1.hdslb.com/bfs/face/9d5e047e428b1cb235ab0e60d6371c0808f5c121.jpg",
      "ownerUserId": null,
      "siteUrl": "https://space.bilibili.com/65564239/channel/collectiondetail?sid=1982929",
      "title": "IT咖啡馆 的 bilibili 合集 合集·GitHub一周热点汇总",
      "type": "feed",
      "url": "rsshub://bilibili/user/collection/65564239/1982929/0/1"
    },
    {
      "description": "Akinokoe 的 bilibili 合集 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59067606177976320",
      "image": "https://i1.hdslb.com/bfs/face/5da869c71ba65e598f296b5ad2c10af52aea5392.jpg",
      "ownerUserId": null,
      "siteUrl": "https://space.bilibili.com/103118875/channel/collectiondetail?sid=1982480",
      "title": "Akinokoe 的 bilibili 合集 合集·AI大模型 LLMs 资讯",
      "type": "feed",
      "url": "rsshub://bilibili/user/collection/103118875/1982480/0/1"
    }
  ]
}
```
