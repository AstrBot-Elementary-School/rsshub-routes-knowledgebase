# 虎扑 - 社区

## Coverage
`index-only`

## Route
- Namespace: `hupu`
- Namespace Name: `虎扑`
- Route Path: `/hupu/bxj/:id?/:order?`
- Route Name: `社区`
- Example: `/hupu/bbs/topic-daily`
- URL: `bbs.hupu.com`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `LogicJake, nczitzk`
- Source Location: `bbs-bxj.ts`
- Source Module: `_None_`

## Description
::: tip
更多社区参见 [社区](https://bbs.hupu.com)
:::

## Parameters
- `id`: 编号，可在对应社区 URL 中找到，默认为#步行街主干道
- `order`: 排序方式，可选 `0` 即 最新回复 或 `1` 即 最新发布，默认为最新发布


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
    "bbs"
  ],
  "description": "::: tip\n更多社区参见 [社区](https://bbs.hupu.com)\n:::",
  "example": "/hupu/bbs/topic-daily",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 7,
  "location": "bbs-bxj.ts",
  "maintainers": [
    "LogicJake",
    "nczitzk"
  ],
  "name": "社区",
  "parameters": {
    "id": "编号，可在对应社区 URL 中找到，默认为#步行街主干道",
    "order": "排序方式，可选 `0` 即 最新回复 或 `1` 即 最新发布，默认为最新发布"
  },
  "path": "/bxj/:id?/:order?",
  "radar": [],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "全村吃饭、白额高脚......应有尽有 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "86934101100237824",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bbs.hupu.com/34-postdate",
      "title": "虎扑社区 - #动物萌宠区",
      "type": "feed",
      "url": "rsshub://hupu/bxj"
    }
  ]
}
```
