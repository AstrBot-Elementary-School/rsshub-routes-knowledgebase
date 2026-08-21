# 观察者网 - 个人主页文章

## Coverage
`index-only`

## Route
- Namespace: `guancha`
- Namespace Name: `观察者网`
- Route Path: `/guancha/personalpage/:uid`
- Route Name: `个人主页文章`
- Example: `/guancha/personalpage/243983`
- URL: `guancha.cn`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `Jeason0228`
- Source Location: `personalpage.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `uid`: 用户id， 可在URL中找到


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
    "new-media"
  ],
  "example": "/guancha/personalpage/243983",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 20,
  "location": "personalpage.ts",
  "maintainers": [
    "Jeason0228"
  ],
  "name": "个人主页文章",
  "parameters": {
    "uid": "用户id， 可在URL中找到"
  },
  "path": "/personalpage/:uid",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "持续低熵 的个人主页 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "62825086347448323",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://app.guancha.cn/user/get-published-list?page_size=20&page_no=1&uid=562778",
      "title": "持续低熵-观察者-风闻社区",
      "type": "feed",
      "url": "rsshub://guancha/personalpage/562778"
    },
    {
      "description": "高志凯频道 的个人主页 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "172226578810915840",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://app.guancha.cn/user/get-published-list?page_size=20&page_no=1&uid=1362536",
      "title": "高志凯频道-观察者-风闻社区",
      "type": "feed",
      "url": "rsshub://guancha/personalpage/1362536"
    }
  ]
}
```
