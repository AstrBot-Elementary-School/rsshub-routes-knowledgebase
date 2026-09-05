# 上海市教育考试院 - 消息

## Coverage
`index-only`

## Route
- Namespace: `shmeea`
- Namespace Name: `上海市教育考试院`
- Route Path: `/shmeea/:id?`
- Route Name: `消息`
- Example: `/shmeea/08000`
- URL: `www.shmeea.edu.cn`
- Language: `_None_`
- Categories: `study`
- Maintainers: `jialinghui, Misaka13514`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
例如：消息速递的网址为 `https://www.shmeea.edu.cn/page/08000/index.html`，则页面 ID 为 `08000`。
:::

::: warning
暂不支持大类分类和[院内动态](https://www.shmeea.edu.cn/page/19000/index.html)
:::

## Parameters
- `id`: 页面 ID，可在 URL 中找到，默认为消息速递


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
    "study"
  ],
  "description": "::: tip\n例如：消息速递的网址为 `https://www.shmeea.edu.cn/page/08000/index.html`，则页面 ID 为 `08000`。\n:::\n\n::: warning\n暂不支持大类分类和[院内动态](https://www.shmeea.edu.cn/page/19000/index.html)\n:::",
  "example": "/shmeea/08000",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 4,
  "location": "index.ts",
  "maintainers": [
    "jialinghui",
    "Misaka13514"
  ],
  "name": "消息",
  "parameters": {
    "id": "页面 ID，可在 URL 中找到，默认为消息速递"
  },
  "path": "/:id?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "上海市教育考试院-消息速递 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "84147473290155008",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.shmeea.edu.cn/page/08000/index.html",
      "title": "上海市教育考试院-消息速递",
      "type": "feed",
      "url": "rsshub://shmeea"
    },
    {
      "description": "上海市教育考试院-消息速递 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "92130275905288192",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.shmeea.edu.cn/page/08000/index.html",
      "title": "上海市教育考试院-消息速递",
      "type": "feed",
      "url": "rsshub://shmeea/08000"
    }
  ]
}
```
