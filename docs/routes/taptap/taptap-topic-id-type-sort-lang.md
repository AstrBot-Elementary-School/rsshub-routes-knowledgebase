# TapTap - 游戏论坛

## Coverage
`index-only`

## Route
- Namespace: `taptap`
- Namespace Name: `TapTap`
- Route Path: `/taptap/topic/:id/:type?/:sort?/:lang?`
- Route Name: `游戏论坛`
- Example: `/taptap/topic/142793/official`
- URL: `www.taptap.io`
- Language: `_None_`
- Categories: `game`
- Maintainers: `hoilc, TonyRL`
- Source Location: `topic.ts`
- Source Module: `_None_`

## Description
| 全部 | 精华  | 官方     | 影片  |
| ---- | ----- | -------- | ----- |
| feed | elite | official | video |

| 发布时间 | 回复时间  | 默认排序 |
| -------- | --------- | -------- |
| created  | commented | default  |

## Parameters
- `id`: 游戏 ID，游戏主页 URL 中获取
- `type`: 论坛版块，默认显示所有帖子，论坛版块 URL 中 `type` 参数，见下表，默认为 `feed`
- `sort`: 排序，见下表，默认为 `created`
- `lang`: 语言，`zh-CN`或`zh-TW`，默认为`zh-CN`


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
  - `taptap.cn/app/:id/topic`
  - `taptap.cn/app/:id`
- `target`: `/topic/:id`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "| 全部 | 精华  | 官方     | 影片  |\n| ---- | ----- | -------- | ----- |\n| feed | elite | official | video |\n\n| 发布时间 | 回复时间  | 默认排序 |\n| -------- | --------- | -------- |\n| created  | commented | default  |",
  "example": "/taptap/topic/142793/official",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 9,
  "location": "topic.ts",
  "maintainers": [
    "hoilc",
    "TonyRL"
  ],
  "name": "游戏论坛",
  "parameters": {
    "id": "游戏 ID，游戏主页 URL 中获取",
    "lang": "语言，`zh-CN`或`zh-TW`，默认为`zh-CN`",
    "sort": "排序，见下表，默认为 `created`",
    "type": "论坛版块，默认显示所有帖子，论坛版块 URL 中 `type` 参数，见下表，默认为 `feed`"
  },
  "path": "/topic/:id/:type?/:sort?/:lang?",
  "radar": [
    {
      "source": [
        "taptap.cn/app/:id/topic",
        "taptap.cn/app/:id"
      ],
      "target": "/topic/:id"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "梦想协奏曲！少女乐团派对！ - undefined - TapTap 论坛 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "108848663019143168",
      "image": "https://img-tc.tapimg.com/market/images/eedb45acdbfa1066fe9b02ba377ff0ef.png",
      "ownerUserId": null,
      "siteUrl": "https://www.taptap.cn/app/67848/topic?type=feed&sort=commented",
      "title": "梦想协奏曲！少女乐团派对！ - undefined - TapTap 论坛",
      "type": "feed",
      "url": "rsshub://taptap/topic/67848/feed/commented/zh-CN"
    },
    {
      "description": "EVE - 官方 - TapTap 论坛 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "256765756479228928",
      "image": "https://img-tc.tapimg.com/market/images/e0e57fdd638a65dd945d795b0f333b47.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.taptap.cn/app/788667/topic?type=official&sort=created",
      "title": "EVE - 官方 - TapTap 论坛",
      "type": "feed",
      "url": "rsshub://taptap/topic/788667/official"
    }
  ]
}
```
