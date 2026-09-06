# 虎扑 - 社区

## Coverage
`index-only`

## Route
- Namespace: `hupu`
- Namespace Name: `虎扑`
- Route Path: `/hupu/bbs/:id?/:order?`
- Route Name: `社区`
- Example: `/hupu/bbs/topic-daily`
- URL: `.hupu.com`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `LogicJake, nczitzk`
- Source Location: `bbs.tsx`
- Source Module: `_None_`

## Description
::: tip
更多社区参见 [社区](https://bbs.hupu.com)
:::

## Parameters
- `id`: 编号，可在对应社区 URL 中找到，默认为#步行街主干道
- `order`: 排序方式，可选 `0` 即 最新回复 或 `1` 即 最新发布，默认为最新回复


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
  - `m.hupu.com/:category`
  - `m.hupu.com/`
- `target`: `/:category`

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
  "heat": 225,
  "location": "bbs.tsx",
  "maintainers": [
    "LogicJake",
    "nczitzk"
  ],
  "name": "社区",
  "parameters": {
    "id": "编号，可在对应社区 URL 中找到，默认为#步行街主干道",
    "order": "排序方式，可选 `0` 即 最新回复 或 `1` 即 最新发布，默认为最新回复"
  },
  "path": [
    "/bbs/:id?/:order?",
    "/bxj/:id?/:order?"
  ],
  "radar": [
    {
      "source": [
        "m.hupu.com/:category",
        "m.hupu.com/"
      ],
      "target": "/:category"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "投资有风险，入市需谨慎 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "66332234198832169",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bbs.hupu.com/stock-postdate",
      "title": "虎扑社区 - #股票区",
      "type": "feed",
      "url": "rsshub://hupu/bbs/stock"
    },
    {
      "description": "逛步行街极易上瘾，请各位JRs注意控制时间 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "55619435859718144",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bbs.hupu.com/topic-daily-postdate",
      "title": "虎扑社区 - #步行街主干道",
      "type": "feed",
      "url": "rsshub://hupu/bbs/topic-daily"
    }
  ]
}
```
