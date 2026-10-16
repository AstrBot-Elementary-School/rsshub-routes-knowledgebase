# 创业邦 - 标签

## Coverage
`index-only`

## Route
- Namespace: `cyzone`
- Namespace Name: `创业邦`
- Route Path: `/cyzone/label/:name`
- Route Name: `标签`
- Example: `/cyzone/label/创业邦周报`
- URL: `cyzone.cn`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `LogicJake, nczitzk`
- Source Location: `label.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `name`: 标签名称，可在对应标签页 URL 中找到


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
  - `cyzone.cn/label/:name`
  - `cyzone.cn/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/cyzone/label/创业邦周报",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 156,
  "location": "label.ts",
  "maintainers": [
    "LogicJake",
    "nczitzk"
  ],
  "name": "标签",
  "parameters": {
    "name": "标签名称，可在对应标签页 URL 中找到"
  },
  "path": "/label/:name",
  "radar": [
    {
      "source": [
        "cyzone.cn/label/:name",
        "cyzone.cn/"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "科技 - 创业邦 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "84442733117971456",
      "image": "https://static.cyzone.cn/img/logo/orange.png",
      "ownerUserId": null,
      "siteUrl": "https://m.cyzone.cn/tag/%E7%A7%91%E6%8A%80",
      "title": "科技 - 创业邦",
      "type": "feed",
      "url": "rsshub://cyzone/label/%E7%A7%91%E6%8A%80"
    },
    {
      "description": "创业邦周报 - 创业邦 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "65378254242899968",
      "image": "https://www.cyzone.cn/undefined",
      "ownerUserId": null,
      "siteUrl": "https://m.cyzone.cn/tag/%E5%88%9B%E4%B8%9A%E9%82%A6%E5%91%A8%E6%8A%A5",
      "title": "创业邦周报 - 创业邦",
      "type": "feed",
      "url": "rsshub://cyzone/label/%E5%88%9B%E4%B8%9A%E9%82%A6%E5%91%A8%E6%8A%A5"
    }
  ]
}
```
