# 微博 - 绿洲用户

## Coverage
`index-only`

## Route
- Namespace: `weibo`
- Namespace Name: `微博`
- Route Path: `/weibo/oasis/user/:userid`
- Route Name: `绿洲用户`
- Example: `/weibo/oasis/user/1990895721`
- URL: `weibo.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `kt286`
- Source Location: `oasis/user.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `userid`: 用户 id, 可在用户主页 URL 中找到


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
  - `m.weibo.cn/u/:uid`
  - `m.weibo.cn/profile/:uid`
- `target`: `/user/:uid`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/weibo/oasis/user/1990895721",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 4,
  "location": "oasis/user.ts",
  "maintainers": [
    "kt286"
  ],
  "name": "绿洲用户",
  "parameters": {
    "userid": "用户 id, 可在用户主页 URL 中找到"
  },
  "path": "/oasis/user/:userid",
  "radar": [
    {
      "source": [
        "m.weibo.cn/u/:uid",
        "m.weibo.cn/profile/:uid"
      ],
      "target": "/user/:uid"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "꒰•̫͡•ོ꒱海岛吃货小海薇∅ - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "154748015616876544",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://oasis.weibo.cn/v1/h5/share?uid=5172654370",
      "title": "丢不盐的粮 - 用户 - 绿洲",
      "type": "feed",
      "url": "rsshub://weibo/oasis/user/5172654370"
    },
    {
      "description": "杂乱无章 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "214594184648932352",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://oasis.weibo.cn/v1/h5/share?uid=3841137060",
      "title": "驿站边 - 用户 - 绿洲",
      "type": "feed",
      "url": "rsshub://weibo/oasis/user/3841137060"
    }
  ]
}
```
