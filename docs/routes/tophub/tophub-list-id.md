# 今日热榜 - 榜单列表

## Coverage
`index-only`

## Route
- Namespace: `tophub`
- Namespace Name: `今日热榜`
- Route Path: `/tophub/list/:id`
- Route Name: `榜单列表`
- Example: `/tophub/list/Om4ejxvxEN`
- URL: `tophub.today`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `akynazh`
- Source Location: `list.tsx`
- Source Module: `_None_`

## Description
::: tip
将榜单条目集合到一个列表中，且有热度排序，可避免推送大量条目。
:::

## Parameters
- `id`: 榜单id，可在 URL 中找到


## Features
- `requireConfig`: [{"description": "", "name": "TOPHUB_COOKIE", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `tophub.today/n/:id`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\n将榜单条目集合到一个列表中，且有热度排序，可避免推送大量条目。\n:::",
  "example": "/tophub/list/Om4ejxvxEN",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "",
        "name": "TOPHUB_COOKIE",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 334,
  "location": "list.tsx",
  "maintainers": [
    "akynazh"
  ],
  "name": "榜单列表",
  "parameters": {
    "id": "榜单id，可在 URL 中找到"
  },
  "path": "/list/:id",
  "radar": [
    {
      "source": [
        "tophub.today/n/:id"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "订阅数：38万+ - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "76104512239628288",
      "image": "https://file.ipadown.com/tophub/assets/images/media/s.weibo.com.png_160x160.png",
      "ownerUserId": null,
      "siteUrl": "https://tophub.today/n/KqndgxeLl9",
      "title": "微博 ‧ 热搜榜",
      "type": "feed",
      "url": "rsshub://tophub/list/KqndgxeLl9"
    },
    {
      "description": "订阅数：22万+ - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "84143549021479936",
      "image": "https://file.ipadown.com/tophub/assets/images/media/toutiao.com.png_160x160.png",
      "ownerUserId": null,
      "siteUrl": "https://tophub.today/n/x9ozB4KoXb",
      "title": "今日头条 ‧ 头条热榜",
      "type": "feed",
      "url": "rsshub://tophub/list/x9ozB4KoXb"
    }
  ]
}
```
