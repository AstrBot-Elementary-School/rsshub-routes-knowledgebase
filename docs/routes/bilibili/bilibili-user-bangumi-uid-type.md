# 哔哩哔哩 bilibili - 用户追番列表

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/bilibili/user/bangumi/:uid/:type?`
- Route Name: `用户追番列表`
- Example: `/bilibili/user/bangumi/208259`
- URL: `www.bilibili.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `wdssmq`
- Source Location: `user-bangumi.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `uid`: 用户 id
- `type`: 1为番，2为剧，留空为1


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
  - `space.bilibili.com/:uid`
- `target`: `/user/bangumi/:uid`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/bilibili/user/bangumi/208259",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 12,
  "location": "user-bangumi.ts",
  "maintainers": [
    "wdssmq"
  ],
  "name": "用户追番列表",
  "parameters": {
    "type": "1为番，2为剧，留空为1",
    "uid": "用户 id"
  },
  "path": "/user/bangumi/:uid/:type?",
  "radar": [
    {
      "source": [
        "space.bilibili.com/:uid"
      ],
      "target": "/user/bangumi/:uid"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "陈睿 的追番列表 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "83012577044568064",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://space.bilibili.com/208259/bangumi",
      "title": "陈睿 的追番列表",
      "type": "feed",
      "url": "rsshub://bilibili/user/bangumi/208259"
    },
    {
      "description": "undefined 的追番列表 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "112858271389438976",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://space.bilibili.com/351180841/bangumi",
      "title": "undefined 的追番列表",
      "type": "feed",
      "url": "rsshub://bilibili/user/bangumi/351180841"
    }
  ]
}
```
