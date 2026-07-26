# 微信小程序 - 公众号（搜狗来源）

## Coverage
`index-only`

## Route
- Namespace: `wechat`
- Namespace Name: `微信小程序`
- Route Path: `/wechat/sogou/:id`
- Route Name: `公众号（搜狗来源）`
- Example: `/wechat/sogou/qimao0908`
- URL: `posts.careerengine.us`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `EthanWng97, pseudoyu`
- Source Location: `sogou.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 公众号 id, 打开 weixin.sogou.com 并搜索相应公众号， 在 URL 中找到 id


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/wechat/sogou/qimao0908",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 60,
  "location": "sogou.ts",
  "maintainers": [
    "EthanWng97",
    "pseudoyu"
  ],
  "name": "公众号（搜狗来源）",
  "parameters": {
    "id": "公众号 id, 打开 weixin.sogou.com 并搜索相应公众号， 在 URL 中找到 id"
  },
  "path": "/sogou/:id",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "运维网工 的微信公众号 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "142542915535418368",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://weixin.sogou.com/weixin?query=gh_b3b43949212c",
      "title": "运维网工 的微信公众号",
      "type": "feed",
      "url": "rsshub://wechat/sogou/gh_b3b43949212c"
    },
    {
      "description": "CJSW 的微信公众号 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "168490238563645440",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://weixin.sogou.com/weixin?query=china_socialwork",
      "title": "CJSW 的微信公众号",
      "type": "feed",
      "url": "rsshub://wechat/sogou/china_socialwork"
    }
  ]
}
```
