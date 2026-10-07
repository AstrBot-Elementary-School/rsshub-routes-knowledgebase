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
- Maintainers: `salviox`
- Source Location: `article.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `uid`: 用户 id，网址上直接可以看到


## Features
- `requireConfig`: [{"description": "什么值得买登录后的 Cookie 值", "name": "SMZDM_COOKIE", "optional": true}]
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
        "name": "SMZDM_COOKIE",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 138,
  "location": "article.ts",
  "maintainers": [
    "salviox"
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
      "description": "中年男人的最后归宿-喜欢盘各种电子包浆的东西 公众号:Panda不是猫 v:westlife995 （备注来意） - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "70353490015745024",
      "image": "https://avatarimg.smzdm.com/default/9256201282/6641eb4fa13d92174-middle.jpg",
      "ownerUserId": null,
      "siteUrl": "https://zhiyou.smzdm.com/member/9256201282/article/",
      "title": "熊猫不是猫QAQ-什么值得买",
      "type": "feed",
      "url": "rsshub://smzdm/article/9256201282"
    },
    {
      "description": "公众号：可爱的小Cherry。擅长于分享NAS、docker、电子数码周边好物。最近打算给家里的家电升升级。v+：Cgakki - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "70353182008669184",
      "image": "https://avatarimg.smzdm.com/default/9674309982/65950b78c0ca96137-middle.jpg",
      "ownerUserId": null,
      "siteUrl": "https://zhiyou.smzdm.com/member/9674309982/article/",
      "title": "可爱的小cherry-什么值得买",
      "type": "feed",
      "url": "rsshub://smzdm/article/9674309982"
    }
  ]
}
```
