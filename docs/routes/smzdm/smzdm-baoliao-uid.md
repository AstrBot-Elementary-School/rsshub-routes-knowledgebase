# 什么值得买 - 用户爆料

## Coverage
`index-only`

## Route
- Namespace: `smzdm`
- Namespace Name: `什么值得买`
- Route Path: `/smzdm/baoliao/:uid`
- Route Name: `用户爆料`
- Example: `/smzdm/baoliao/7367111021`
- URL: `post.smzdm.com`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `nczitzk`
- Source Location: `baoliao.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `uid`: 用户id，网址上直接可以看到


## Features
- `requireConfig`: [{"description": "什么值得买登录后的 Cookie 值", "name": "SMZDM_COOKIE"}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `zhiyou.smzdm.com/member/:uid/baoliao`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "example": "/smzdm/baoliao/7367111021",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "什么值得买登录后的 Cookie 值",
        "name": "SMZDM_COOKIE"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 59,
  "location": "baoliao.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "用户爆料",
  "parameters": {
    "uid": "用户id，网址上直接可以看到"
  },
  "path": "/baoliao/:uid",
  "radar": [
    {
      "source": [
        "zhiyou.smzdm.com/member/:uid/baoliao"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": "信小兔的爆料 - 什么值得买 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "63858618178298962",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://zhiyou.smzdm.com/member/9687682701/baoliao/",
      "title": "信小兔的爆料 - 什么值得买",
      "type": "feed",
      "url": "rsshub://smzdm/baoliao/9687682701"
    },
    {
      "description": "AWW-CH的爆料 - 什么值得买 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "78644582017168384",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://zhiyou.smzdm.com/member/9279270364/baoliao/",
      "title": "AWW-CH的爆料 - 什么值得买",
      "type": "feed",
      "url": "rsshub://smzdm/baoliao/9279270364"
    }
  ]
}
```
