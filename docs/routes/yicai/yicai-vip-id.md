# 第一财经 - VIP 频道

## Coverage
`index-only`

## Route
- Namespace: `yicai`
- Namespace Name: `第一财经`
- Route Path: `/yicai/vip/:id?`
- Route Name: `VIP 频道`
- Example: `/yicai/vip/428`
- URL: `yicai.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `vip.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 频道 id，可在对应频道页中找到，默认为一元点金


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
  - `yicai.com/vip/product/:id`
  - `yicai.com/`
- `target`: `/vip/:id`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/yicai/vip/428",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 15,
  "location": "vip.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "VIP 频道",
  "parameters": {
    "id": "频道 id，可在对应频道页中找到，默认为一元点金"
  },
  "path": "/vip/:id?",
  "radar": [
    {
      "source": [
        "yicai.com/vip/product/:id",
        "yicai.com/"
      ],
      "target": "/vip/:id"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "第一财经VIP频道 - 第一财经杂志丨YiMagazine | 探索明亮的商业世界 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "107406669394481152",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.yicai.com/vip/product/55",
      "title": "第一财经VIP频道 - 第一财经杂志丨YiMagazine | 探索明亮的商业世界",
      "type": "feed",
      "url": "rsshub://yicai/vip/55"
    },
    {
      "description": "第一财经VIP频道 - 一元点金 | 即时热点 单篇精选 - Powered by RSSHub",
      "errorAt": "2026-01-06T15:11:39.949Z",
      "errorMessage": "[GET] \"https://www.yicai.com/vip/product/428\": 404 Not Found\n",
      "id": "62792430599606272",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.yicai.com/vip/product/428",
      "title": "第一财经VIP频道 - 一元点金 | 即时热点 单篇精选",
      "type": "feed",
      "url": "rsshub://yicai/vip/428"
    }
  ]
}
```
