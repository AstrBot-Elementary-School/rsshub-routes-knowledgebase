# The Initium - 栏目

## Coverage
`index-only`

## Route
- Namespace: `theinitium`
- Namespace Name: `The Initium`
- Route Path: `/theinitium/channel/:type?/:language?`
- Route Name: `栏目`
- Example: `/theinitium/channel/latest`
- URL: `theinitium.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `prnake, mintyfrankie, pseudoyu`
- Source Location: `channel.ts`
- Source Module: `_None_`

## Description
Type 栏目（对应 Ghost 标签）：

| 最新   | 速递     | 评论    | 国际          | 大陆     | 香港     | 台湾   | 科技       | 专题    | 日报        | 周报   |
| ------ | -------- | ------- | ------------- | -------- | -------- | ------ | ---------- | ------- | ----------- | ------ |
| latest | whatsnew | opinion | international | mainland | hongkong | taiwan | technology | feature | daily-brief | weekly |

::: tip
设置环境变量 `INITIUM_MEMBER_COOKIE` 可获取付费文章全文。
:::

## Parameters
- `type`: 栏目，缺省为最新（latest）
- `language`: 语言，简体`zh-hans`，繁体`zh-hant`，缺省为不限


## Features
- `requireConfig`: [{"description": "端传媒会员登录后的 Cookie，用于获取付费文章全文。获取方式：登录 theinitium.com 后，从浏览器开发者工具中复制 Cookie。", "name": "INITIUM_MEMBER_COOKIE", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `theinitium.com/latest/`
- `target`: `/channel/latest`
### Rule 2
- `source`:
  - `theinitium.com/tag/:type`
- `target`: `/channel/:type`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "Type 栏目（对应 Ghost 标签）：\n\n| 最新   | 速递     | 评论    | 国际          | 大陆     | 香港     | 台湾   | 科技       | 专题    | 日报        | 周报   |\n| ------ | -------- | ------- | ------------- | -------- | -------- | ------ | ---------- | ------- | ----------- | ------ |\n| latest | whatsnew | opinion | international | mainland | hongkong | taiwan | technology | feature | daily-brief | weekly |\n\n::: tip\n设置环境变量 `INITIUM_MEMBER_COOKIE` 可获取付费文章全文。\n:::",
  "example": "/theinitium/channel/latest",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "端传媒会员登录后的 Cookie，用于获取付费文章全文。获取方式：登录 theinitium.com 后，从浏览器开发者工具中复制 Cookie。",
        "name": "INITIUM_MEMBER_COOKIE",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 130,
  "location": "channel.ts",
  "maintainers": [
    "prnake",
    "mintyfrankie",
    "pseudoyu"
  ],
  "name": "栏目",
  "parameters": {
    "language": "语言，简体`zh-hans`，繁体`zh-hant`，缺省为不限",
    "type": "栏目，缺省为最新（latest）"
  },
  "path": "/channel/:type?/:language?",
  "radar": [
    {
      "source": [
        "theinitium.com/latest/"
      ],
      "target": "/channel/latest"
    },
    {
      "source": [
        "theinitium.com/tag/:type"
      ],
      "target": "/channel/:type"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "端傳媒 - 最新 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41443203209057310",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://theinitium.com/latest/",
      "title": "端傳媒 - 最新",
      "type": "feed",
      "url": "rsshub://theinitium/channel/latest/zh-hans"
    },
    {
      "description": "端傳媒 - 专题 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "56674476083111936",
      "image": "https://d32kak7w9u5ewj.cloudfront.net/media/channel/2020/09/a371f1d3b70c4006a88cc12d127e1f52.jpg",
      "ownerUserId": null,
      "siteUrl": "https://theinitium.com/tag/report/",
      "title": "端傳媒 - 专题",
      "type": "feed",
      "url": "rsshub://theinitium/channel/feature/zh-hans"
    }
  ],
  "url": "theinitium.com"
}
```
