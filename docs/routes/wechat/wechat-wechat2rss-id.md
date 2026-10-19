# 微信小程序 - 公众号（Wechat2RSS 来源）

## Coverage
`index-only`

## Route
- Namespace: `wechat`
- Namespace Name: `微信小程序`
- Route Path: `/wechat/wechat2rss/:id`
- Route Name: `公众号（Wechat2RSS 来源）`
- Example: `/wechat/wechat2rss/5b925323244e9737c39285596c53e3a2f4a30774`
- URL: `posts.careerengine.us`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `wechat2rss.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 公众号 id，打开 `https://wechat2rss.xlab.app/posts/list/`，在 URL 中找到 id；注意不是公众号页的 id，而是订阅的 id


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
  "example": "/wechat/wechat2rss/5b925323244e9737c39285596c53e3a2f4a30774",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 407,
  "location": "wechat2rss.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "公众号（Wechat2RSS 来源）",
  "parameters": {
    "id": "公众号 id，打开 `https://wechat2rss.xlab.app/posts/list/`，在 URL 中找到 id；注意不是公众号页的 id，而是订阅的 id"
  },
  "path": "/wechat2rss/:id",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "腾讯技术官方号。腾讯技术创新、前沿领域发布解读平台。 (wechat feed made by @ttttmr https://wechat2rss.xlab.app) - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "56559522756173824",
      "image": "https://wx.qlogo.cn/mmhead/Iic9WLWEQMg2jTKicld7jhiagcz7jJxuYcpjicxAAiaVaNpdIiabCLIxOHIZFVsWH3cRNQjLF1TBznTJc/0",
      "ownerUserId": null,
      "siteUrl": "https://wechat2rss.xlab.app/feed/9685937b45fe9c7a526dbc32e4f24ba879a65b9a.xml",
      "title": "腾讯技术工程",
      "type": "feed",
      "url": "rsshub://wechat/wechat2rss/9685937b45fe9c7a526dbc32e4f24ba879a65b9a"
    },
    {
      "description": "提供B站相关技术的介绍和讲解 (wechat feed made by @ttttmr https://wechat2rss.xlab.app) - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "44004534411339776",
      "image": "https://wx.qlogo.cn/mmhead/VHU8bI7BOJAmaJ0o4FjqrnRrcK84tvX1kNLl9NibQnTdzvIicOAAicZrqXxKzAkPuxcUibe6PEVCmzg/0",
      "ownerUserId": null,
      "siteUrl": "https://wechat2rss.xlab.app/feed/434235d4815fdb8447ff3127fc053ceb8b3aada6.xml",
      "title": "哔哩哔哩技术",
      "type": "feed",
      "url": "rsshub://wechat/wechat2rss/434235d4815fdb8447ff3127fc053ceb8b3aada6"
    }
  ]
}
```
