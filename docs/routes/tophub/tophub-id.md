# 今日热榜 - 榜单

## Coverage
`index-only`

## Route
- Namespace: `tophub`
- Namespace Name: `今日热榜`
- Route Path: `/tophub/:id`
- Route Name: `榜单`
- Example: `/tophub/Om4ejxvxEN`
- URL: `tophub.today`
- Language: `_None_`
- Categories: `new-media, popular`
- Maintainers: `LogicJake`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

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
    "new-media",
    "popular"
  ],
  "example": "/tophub/Om4ejxvxEN",
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
  "heat": 3527,
  "location": "index.ts",
  "maintainers": [
    "LogicJake"
  ],
  "name": "榜单",
  "parameters": {
    "id": "榜单id，可在 URL 中找到"
  },
  "path": "/:id",
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
      "description": "订阅数：33万+ - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "63099316103761920",
      "image": "https://file.ipadown.com/tophub/assets/images/media/mp.weixin.qq.com.png_160x160.png",
      "ownerUserId": null,
      "siteUrl": "https://tophub.today/n/WnBe01o371",
      "title": "微信 ‧ 24h热文榜",
      "type": "feed",
      "url": "rsshub://tophub/WnBe01o371"
    },
    {
      "description": "订阅数：19万+ - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "61088973762758656",
      "image": "https://file.ipadown.com/tophub/assets/images/media/tieba.baidu.com.png_160x160.png",
      "ownerUserId": null,
      "siteUrl": "https://tophub.today/n/Om4ejxvxEN",
      "title": "百度贴吧 ‧ 热议榜",
      "type": "feed",
      "url": "rsshub://tophub/Om4ejxvxEN"
    }
  ]
}
```
