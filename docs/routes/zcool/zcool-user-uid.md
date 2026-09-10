# 站酷 - 用户作品

## Coverage
`index-only`

## Route
- Namespace: `zcool`
- Namespace Name: `站酷`
- Route Path: `/zcool/user/:uid`
- Route Name: `用户作品`
- Example: `/zcool/user/baiyong`
- URL: `www.zcool.com.cn`
- Language: `_None_`
- Categories: `design, popular`
- Maintainers: `junbaor`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
例如:

站酷的个人主页 `https://baiyong.zcool.com.cn` 对应 rss 路径 `/zcool/user/baiyong`

站酷的个人主页 `https://www.zcool.com.cn/u/568339` 对应 rss 路径 `/zcool/user/568339`

## Parameters
- `uid`: 个性域名前缀或者用户ID


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
  - `www.zcool.com.cn/u/:id`
- `target`: `/user/:id`

## Raw JSON
```json
{
  "categories": [
    "design",
    "popular"
  ],
  "description": "例如:\n\n站酷的个人主页 `https://baiyong.zcool.com.cn` 对应 rss 路径 `/zcool/user/baiyong`\n\n站酷的个人主页 `https://www.zcool.com.cn/u/568339` 对应 rss 路径 `/zcool/user/568339`",
  "example": "/zcool/user/baiyong",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1917,
  "location": "user.ts",
  "maintainers": [
    "junbaor"
  ],
  "name": "用户作品",
  "parameters": {
    "uid": "个性域名前缀或者用户ID"
  },
  "path": "/user/:uid",
  "radar": [
    {
      "source": [
        "www.zcool.com.cn/u/:id"
      ],
      "target": "/user/:id"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "北京设计爱好者,抖音设计中心的创作者主页,共上传26组创作,热招 投递简历ued-recruit@bytedance.com,想找北京设计爱好者,就来站酷ZCOOL. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "58346915466474547",
      "image": "https://img.zcool.cn/community/011e675dc3931ba801209e1f55764e.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.zcool.com.cn/u/16232491",
      "title": "抖音设计中心创作者主页_北京设计爱好者-站酷ZCOOL",
      "type": "feed",
      "url": "rsshub://zcool/user/16232491"
    },
    {
      "description": "深圳设计爱好者,腾讯ISUX的创作者主页,共上传251组创作,想找深圳设计爱好者,就来站酷ZCOOL. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "58346915462280198",
      "image": "https://img.zcool.cn/community/01272c5bf61a14a80121ab5dc54fad.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.zcool.com.cn/u/1936779",
      "title": "腾讯ISUX创作者主页_深圳设计爱好者-站酷ZCOOL",
      "type": "feed",
      "url": "rsshub://zcool/user/1936779"
    }
  ],
  "view": 2
}
```
