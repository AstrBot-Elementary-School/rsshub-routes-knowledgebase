# 蜻蜓 FM - 播客

## Coverage
`index-only`

## Route
- Namespace: `qingting`
- Namespace Name: `蜻蜓 FM`
- Route Path: `/qingting/podcast/:id`
- Route Name: `播客`
- Example: `/qingting/podcast/293411`
- URL: `qingting.fm`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `RookieZoe, huyyi, pseudoyu`
- Source Location: `podcast.ts`
- Source Module: `_None_`

## Description
获取的播放 URL 有效期只有 1 天，需要开启播客 APP 的自动下载功能。

## Parameters
- `id`: 专辑id, 可在专辑页 URL 中找到


## Features
- `supportPodcast`: true
- `requireConfig`: [{"description": "用户id， 部分专辑需要会员身份，用户id可以通过从网页端登录蜻蜓fm后使用开发者工具，在控制台中运行JSON.parse(localStorage.getItem(\"user\")).qingting_id获取", "name": "QINGTING_ID", "optional": true}]

## Radar
### Rule 1
- `source`:
  - `qingting.fm/channels/:id`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "获取的播放 URL 有效期只有 1 天，需要开启播客 APP 的自动下载功能。",
  "example": "/qingting/podcast/293411",
  "features": {
    "requireConfig": [
      {
        "description": "用户id， 部分专辑需要会员身份，用户id可以通过从网页端登录蜻蜓fm后使用开发者工具，在控制台中运行JSON.parse(localStorage.getItem(\"user\")).qingting_id获取",
        "name": "QINGTING_ID",
        "optional": true
      }
    ],
    "supportPodcast": true
  },
  "heat": 53,
  "location": "podcast.ts",
  "maintainers": [
    "RookieZoe",
    "huyyi",
    "pseudoyu"
  ],
  "name": "播客",
  "parameters": {
    "id": "专辑id, 可在专辑页 URL 中找到"
  },
  "path": "/podcast/:id",
  "radar": [
    {
      "source": [
        "qingting.fm/channels/:id"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "经典音乐广播FM107.9 佳乐的怀旧经典 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "97644308217505792",
      "image": "http://pic.qtfm.cn/2015/0717/20150717165821696.jpg!400",
      "ownerUserId": null,
      "siteUrl": "https://www.qingting.fm/channels/107970",
      "title": "佳乐的怀旧经典 - 蜻蜓FM",
      "type": "feed",
      "url": "rsshub://qingting/podcast/107970"
    },
    {
      "description": "这里有局座从未讲过的独家观点，热点问题深度剖析，抽丝剥茧解读国际风云大势。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "63145503255841792",
      "image": "http://pic.qtfm.cn/channel/2020/04/20/729ae2b14a19657d635b9306838b8aec.jpg!400",
      "ownerUserId": null,
      "siteUrl": "https://www.qingting.fm/channels/293411",
      "title": "张召忠开讲【典藏版】 - 蜻蜓FM",
      "type": "feed",
      "url": "rsshub://qingting/podcast/293411"
    }
  ]
}
```
