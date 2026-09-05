# 虎嗅 - 用户

## Coverage
`index-only`

## Route
- Namespace: `huxiu`
- Namespace Name: `虎嗅`
- Route Path: `/huxiu/author/:id/:type?`
- Route Name: `用户`
- Example: `/huxiu/member/2313050`
- URL: `huxiu.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `member.ts`
- Source Module: `_None_`

## Description
| TA 的文章 | TA 的 24 小时 |
| --------- | ------------- |
| article   | moment        |

## Parameters
- `id`: 用户 id，可在对应用户页 URL 中找到


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
  "description": "| TA 的文章 | TA 的 24 小时 |\n| --------- | ------------- |\n| article   | moment        |",
  "example": "/huxiu/member/2313050",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": true,
    "supportScihub": false
  },
  "heat": 44,
  "location": "member.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "用户",
  "parameters": {
    "id": "用户 id，可在对应用户页 URL 中找到"
  },
  "path": [
    "/author/:id/:type?",
    "/member/:id/:type?"
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "青年的发问与探寻 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "66028011830664243",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.huxiu.com/member/3073625.html",
      "title": "青年志Youthology的个人中心-虎嗅网",
      "type": "feed",
      "url": "rsshub://huxiu/author/3073625"
    },
    {
      "description": "野生社会观察员 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "129188571039811584",
      "image": "https://img.huxiucdn.com/auth/data/avatar/001/51/52/29_1703563667.jpeg",
      "ownerUserId": null,
      "siteUrl": "https://www.huxiu.com/member/1515229.html",
      "title": "虎嗅用户-刘知趣",
      "type": "feed",
      "url": "rsshub://huxiu/author/1515229"
    }
  ]
}
```
