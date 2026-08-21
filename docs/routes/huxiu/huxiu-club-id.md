# 虎嗅 - 源流

## Coverage
`index-only`

## Route
- Namespace: `huxiu`
- Namespace Name: `虎嗅`
- Route Path: `/huxiu/club/:id`
- Route Name: `源流`
- Example: `/huxiu/club/1161`
- URL: `huxiu.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk, TimoYoung`
- Source Location: `club.ts`
- Source Module: `_None_`

## Description
更多源流请参见 [源流](https://www.huxiu.com/club)

## Parameters
- `id`: 源流 id，可在对应源流页 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: true
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "更多源流请参见 [源流](https://www.huxiu.com/club)",
  "example": "/huxiu/club/1161",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": true,
    "supportScihub": false
  },
  "heat": 6,
  "location": "club.ts",
  "maintainers": [
    "nczitzk",
    "TimoYoung"
  ],
  "name": "源流",
  "parameters": {
    "id": "源流 id，可在对应源流页 URL 中找到"
  },
  "path": "/club/:id",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "获取最新行业资讯，十五分钟尽知天下事。本栏目由虎嗅内容运营团队出品。 - Powered by RSSHub",
      "errorAt": "2026-08-18T14:08:42.788Z",
      "errorMessage": "Failed to fetch\n",
      "id": "61703274008210432",
      "image": "https://img.huxiucdn.com/img/brief/202305/08/172636853912.png",
      "ownerUserId": null,
      "siteUrl": "https://www.huxiu.com/club/1000.html",
      "title": "虎嗅源流-虎嗅报童",
      "type": "feed",
      "url": "rsshub://huxiu/club/1000"
    },
    {
      "description": "那个NG，一个努力勾勒世界轮廓的账号。在吵闹的世界里，真相在沉默之中，我们不提供确切的答案，只分享自由的迟疑瞬间。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "55873602868576279",
      "image": "https://img.huxiucdn.com/img/brief/202305/04/162933149599.jpeg",
      "ownerUserId": null,
      "siteUrl": "https://www.huxiu.com/club/1002.html",
      "title": "虎嗅源流-那個NG",
      "type": "feed",
      "url": "rsshub://huxiu/club/1002"
    }
  ]
}
```
