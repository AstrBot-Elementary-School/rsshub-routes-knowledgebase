# 斗鱼直播 - 鱼吧帖子

## Coverage
`index-only`

## Route
- Namespace: `douyu`
- Namespace Name: `斗鱼直播`
- Route Path: `/douyu/group/:id/:sort?`
- Route Name: `鱼吧帖子`
- Example: `/douyu/group/1011`
- URL: `www.douyu.com`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `nczitzk`
- Source Location: `group.ts`
- Source Module: `_None_`

## Description
| 回复时间排序 | 发布时间排序 |
| ------------ | ------------ |
| 1            | 2            |

## Parameters
- `id`: 鱼吧 id，可在鱼吧页 URL 中找到
- `sort`: 排序方式，见下表，默认为发布时间排序


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
  - `yuba.douyu.com/group/:id`
  - `yuba.douyu.com/group/newself/:id`
  - `yuba.douyu.com/group/newall/:id`
  - `yuba.douyu.com/`
- `target`: `/group/:id`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "description": "| 回复时间排序 | 发布时间排序 |\n| ------------ | ------------ |\n| 1            | 2            |",
  "example": "/douyu/group/1011",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 11,
  "location": "group.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "鱼吧帖子",
  "parameters": {
    "id": "鱼吧 id，可在鱼吧页 URL 中找到",
    "sort": "排序方式，见下表，默认为发布时间排序"
  },
  "path": "/group/:id/:sort?",
  "radar": [
    {
      "source": [
        "yuba.douyu.com/group/:id",
        "yuba.douyu.com/group/newself/:id",
        "yuba.douyu.com/group/newall/:id",
        "yuba.douyu.com/"
      ],
      "target": "/group/:id"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "yyfyyf的鱼吧 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "62342415686604800",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://yuba.douyu.com/group/newself/534",
      "title": "斗鱼鱼吧 - yyfyyf",
      "type": "feed",
      "url": "rsshub://douyu/group/534"
    },
    {
      "description": "洞主的鱼吧 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "69260526927299584",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://yuba.douyu.com/group/newall/199511",
      "title": "斗鱼鱼吧 - 洞主丨歌神洞庭湖",
      "type": "feed",
      "url": "rsshub://douyu/group/199511/1"
    }
  ]
}
```
