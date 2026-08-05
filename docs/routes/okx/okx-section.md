# 欧易 OKX - 公告

## Coverage
`index-only`

## Route
- Namespace: `okx`
- Namespace Name: `欧易 OKX`
- Route Path: `/okx/:section?`
- Route Name: `公告`
- Example: `/okx/new-listings`
- URL: `www.okx.com/zh-hans`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `lxl66566`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `section`: {"default": "latest-announcements", "description": "公告版块", "options": [{"label": "最新公告", "value": "latest-announcements"}, {"label": "新币种上线", "value": "new-listings"}, {"label": "币对下线", "value": "delistings"}, {"label": "交易规则更新", "value": "trading-updates"}, {"label": "充提暂停/恢复公告", "value": "deposit-withdrawal-suspension-resumption"}, {"label": "C2C 公告", "value": "p2p-trading"}, {"label": "Web3", "value": "web3"}, {"label": "赚币", "value": "earn"}, {"label": "Jumpstart", "value": "jumpstart"}, {"label": "API公告", "value": "api"}, {"label": "OKB销毁", "value": "okb-buy-back-burn"}, {"label": "其他", "value": "others"}]}


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
  - `www.okx.com/zh-hans/help/section/:section`
- `target`: `/:section`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/okx/new-listings",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 112,
  "location": "index.ts",
  "maintainers": [
    "lxl66566"
  ],
  "name": "公告",
  "parameters": {
    "section": {
      "default": "latest-announcements",
      "description": "公告版块",
      "options": [
        {
          "label": "最新公告",
          "value": "latest-announcements"
        },
        {
          "label": "新币种上线",
          "value": "new-listings"
        },
        {
          "label": "币对下线",
          "value": "delistings"
        },
        {
          "label": "交易规则更新",
          "value": "trading-updates"
        },
        {
          "label": "充提暂停/恢复公告",
          "value": "deposit-withdrawal-suspension-resumption"
        },
        {
          "label": "C2C 公告",
          "value": "p2p-trading"
        },
        {
          "label": "Web3",
          "value": "web3"
        },
        {
          "label": "赚币",
          "value": "earn"
        },
        {
          "label": "Jumpstart",
          "value": "jumpstart"
        },
        {
          "label": "API公告",
          "value": "api"
        },
        {
          "label": "OKB销毁",
          "value": "okb-buy-back-burn"
        },
        {
          "label": "其他",
          "value": "others"
        }
      ]
    }
  },
  "path": "/:section?",
  "radar": [
    {
      "source": [
        "www.okx.com/zh-hans/help/section/:section"
      ],
      "target": "/:section"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "最新公告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "114341296718629888",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.okx.com/zh-hans/help/section/announcements-latest-announcements",
      "title": "最新公告",
      "type": "feed",
      "url": "rsshub://okx/latest-announcements"
    },
    {
      "description": "最新公告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "113827262636876800",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.okx.com/zh-hans/help/section/announcements-latest-announcements",
      "title": "最新公告",
      "type": "feed",
      "url": "rsshub://okx"
    }
  ]
}
```
