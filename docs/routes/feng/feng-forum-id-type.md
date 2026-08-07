# 威锋 - 社区

## Coverage
`index-only`

## Route
- Namespace: `feng`
- Namespace Name: `威锋`
- Route Path: `/feng/forum/:id/:type?`
- Route Name: `社区`
- Example: `/feng/forum/1`
- URL: `feng.com`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `TonyRL`
- Source Location: `forum.tsx`
- Source Module: `_None_`

## Description
| 最新回复 | 最新发布 | 热门 | 精华    |
| -------- | -------- | ---- | ------- |
| newest   | all      | hot  | essence |

## Parameters
- `id`: 版块 ID，可在版块 URL 找到
- `type`: 排序，见下表，默认为 `all`


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
  - `feng.com/forum/photo/:id`
  - `feng.com/forum/:id`
- `target`: `/forum/:id`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "description": "| 最新回复 | 最新发布 | 热门 | 精华    |\n| -------- | -------- | ---- | ------- |\n| newest   | all      | hot  | essence |",
  "example": "/feng/forum/1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 205,
  "location": "forum.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "name": "社区",
  "parameters": {
    "id": "版块 ID，可在版块 URL 找到",
    "type": "排序，见下表，默认为 `all`"
  },
  "path": "/forum/:id/:type?",
  "radar": [
    {
      "source": [
        "feng.com/forum/photo/:id",
        "feng.com/forum/:id"
      ],
      "target": "/forum/:id"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "一个壁纸换一个心情~ 将你喜欢的壁纸分享给大家吧。本区不打水印。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "60948185395432448",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.feng.com/forum/24",
      "title": "壁纸分享区 - 社区 - 威锋 - 千万果粉大本营",
      "type": "feed",
      "url": "rsshub://feng/forum/24"
    },
    {
      "description": "Macbook、MacBook Pro 、iMac、iMac Pro、Mac mini、Mac Pro 地球上最强的电脑。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "60941909445770240",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.feng.com/forum/23",
      "title": "MacBook/iMac - 社区 - 威锋 - 千万果粉大本营",
      "type": "feed",
      "url": "rsshub://feng/forum/23"
    }
  ]
}
```
