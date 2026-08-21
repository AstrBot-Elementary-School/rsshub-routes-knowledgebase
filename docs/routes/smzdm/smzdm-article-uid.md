# 什么值得买 - 用户文章

## Coverage
`index-only`

## Route
- Namespace: `smzdm`
- Namespace Name: `什么值得买`
- Route Path: `/smzdm/article/:uid`
- Route Name: `用户文章`
- Example: `/smzdm/article/6902738986`
- URL: `post.smzdm.com`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `xfangbao`
- Source Location: `article.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `uid`: 用户 id，网址上直接可以看到


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
  - `zhiyou.smzdm.com/member/:uid/article`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "example": "/smzdm/article/6902738986",
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
  "heat": 141,
  "location": "article.ts",
  "maintainers": [
    "xfangbao"
  ],
  "name": "用户文章",
  "parameters": {
    "uid": "用户 id，网址上直接可以看到"
  },
  "path": "/article/:uid",
  "radar": [
    {
      "source": [
        "zhiyou.smzdm.com/member/:uid/article"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": "可爱的小cherry-什么值得买 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "70353182008669184",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://zhiyou.smzdm.com/member/9674309982/article/",
      "title": "可爱的小cherry-什么值得买",
      "type": "feed",
      "url": "rsshub://smzdm/article/9674309982"
    },
    {
      "description": "熊猫不是猫QAQ-什么值得买 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "70353490015745024",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://zhiyou.smzdm.com/member/9256201282/article/",
      "title": "熊猫不是猫QAQ-什么值得买",
      "type": "feed",
      "url": "rsshub://smzdm/article/9256201282"
    }
  ]
}
```
