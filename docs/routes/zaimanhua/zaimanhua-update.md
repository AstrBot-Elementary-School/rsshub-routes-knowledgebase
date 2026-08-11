# 再漫画 - 最近更新

## Coverage
`index-only`

## Route
- Namespace: `zaimanhua`
- Namespace Name: `再漫画`
- Route Path: `/zaimanhua/update`
- Route Name: `最近更新`
- Example: `/zaimanhua/update`
- URL: `manhua.zaimanhua.com`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `kjasn`
- Source Location: `update.ts`
- Source Module: `_None_`

## Description
::: Warning
建议设置`ZAIMANHUA_TOKEN`环境变量以使用 API 授权访问。且由于源网站本身的限制，建议尽量在部署于中国大陆网络内的 RSSHub 节点中使用本路由。若在海外网络环境中使用，即使设置了`ZAIMANHUA_TOKEN`环境变量，也可能无法获取全部漫画。
:::

## Parameters
_None_


## Features
- `requireConfig`: [{"description": "可从浏览器开发者工具中抓取站点请求头 `Authorization` 的 Bearer token，并配置为环境变量。可设置为完整值 `Bearer <token>`，或仅设置 token 由路由自动补齐 `Bearer ` 前缀。", "name": "ZAIMANHUA_TOKEN", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `manhua.zaimanhua.com/update`
- `target`: `/update`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "description": "::: Warning\n建议设置`ZAIMANHUA_TOKEN`环境变量以使用 API 授权访问。且由于源网站本身的限制，建议尽量在部署于中国大陆网络内的 RSSHub 节点中使用本路由。若在海外网络环境中使用，即使设置了`ZAIMANHUA_TOKEN`环境变量，也可能无法获取全部漫画。\n:::",
  "example": "/zaimanhua/update",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": [
      {
        "description": "可从浏览器开发者工具中抓取站点请求头 `Authorization` 的 Bearer token，并配置为环境变量。可设置为完整值 `Bearer <token>`，或仅设置 token 由路由自动补齐 `Bearer ` 前缀。",
        "name": "ZAIMANHUA_TOKEN",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "update.ts",
  "maintainers": [
    "kjasn"
  ],
  "name": "最近更新",
  "path": "/update",
  "radar": [
    {
      "source": [
        "manhua.zaimanhua.com/update"
      ],
      "target": "/update"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "再漫画 - 最近更新 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "143481497751851008",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://manhua.zaimanhua.com/update",
      "title": "再漫画 - 最近更新",
      "type": "feed",
      "url": "rsshub://zaimanhua/update"
    }
  ]
}
```
