# 第一财经 - 关注

## Coverage
`index-only`

## Route
- Namespace: `yicai`
- Namespace Name: `第一财经`
- Route Path: `/yicai/feed/:id?`
- Route Name: `关注`
- Example: `/yicai/feed/669`
- URL: `yicai.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `feed.ts`
- Source Module: `_None_`

## Description
::: tip
全部主题词见 [此处](https://www.yicai.com/feed/alltheme)
:::

## Parameters
- `id`: 主题 id，可在对应主题页中找到，默认为一财早报


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
  - `yicai.com/feed/:id`
  - `yicai.com/feed`
- `target`: `/feed/:id`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "::: tip\n全部主题词见 [此处](https://www.yicai.com/feed/alltheme)\n:::",
  "example": "/yicai/feed/669",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 107,
  "location": "feed.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "关注",
  "parameters": {
    "id": "主题 id，可在对应主题页中找到，默认为一财早报"
  },
  "path": "/feed/:id?",
  "radar": [
    {
      "source": [
        "yicai.com/feed/:id",
        "yicai.com/feed"
      ],
      "target": "/feed/:id"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "第一财经主题 - 一财早报 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "57265298134029312",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.yicai.com/feed/669",
      "title": "第一财经主题 - 一财早报",
      "type": "feed",
      "url": "rsshub://yicai/feed/669"
    },
    {
      "description": "第一财经主题 - 一财早报 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "149537784167521280",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.yicai.com/feed/669",
      "title": "第一财经主题 - 一财早报",
      "type": "feed",
      "url": "rsshub://yicai/feed"
    }
  ]
}
```
