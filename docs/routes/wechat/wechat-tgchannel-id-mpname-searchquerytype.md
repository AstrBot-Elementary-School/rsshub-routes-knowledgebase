# 微信小程序 - 公众号（Telegram 频道来源）

## Coverage
`index-only`

## Route
- Namespace: `wechat`
- Namespace Name: `微信小程序`
- Route Path: `/wechat/tgchannel/:id/:mpName?/:searchQueryType?`
- Route Name: `公众号（Telegram 频道来源）`
- Example: `/wechat/tgchannel/lifeweek`
- URL: `posts.careerengine.us`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `LogicJake, Rongronggg9`
- Source Location: `tgchannel.ts`
- Source Module: `_None_`

## Description
| 搜索查询类型 | 将使用的搜索关键字 |            适用于           |
| :----------: | :----------------: | :-------------------------: |
|      `0`     |     (禁用搜索)     |       所有情况 (默认)       |
|      `1`     |     公众号全名     | 未启用 efb-patch-middleware |
|      `2`     |     #公众号全名    | 已启用 efb-patch-middleware |

::: tip
启用搜索有助于在订阅了过多公众号的频道里有效筛选，不易因为大量公众号同时推送导致一些公众号消息被遗漏，但必须正确选择搜索查询类型，否则会搜索失败。
:::

::: warning
该方法需要通过 efb 进行频道绑定，具体操作见 <https://github.com/DIYgod/RSSHub/issues/2172>
:::

## Parameters
- `id`: 公众号绑定频道 id
- `mpName`: 欲筛选的公众号全名（URL-encoded，精确匹配），在频道订阅了多个公众号时可选用
- `searchQueryType`: 搜索查询类型，见下表


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
    "new-media"
  ],
  "description": "| 搜索查询类型 | 将使用的搜索关键字 |            适用于           |\n| :----------: | :----------------: | :-------------------------: |\n|      `0`     |     (禁用搜索)     |       所有情况 (默认)       |\n|      `1`     |     公众号全名     | 未启用 efb-patch-middleware |\n|      `2`     |     #公众号全名    | 已启用 efb-patch-middleware |\n\n::: tip\n启用搜索有助于在订阅了过多公众号的频道里有效筛选，不易因为大量公众号同时推送导致一些公众号消息被遗漏，但必须正确选择搜索查询类型，否则会搜索失败。\n:::\n\n::: warning\n该方法需要通过 efb 进行频道绑定，具体操作见 <https://github.com/DIYgod/RSSHub/issues/2172>\n:::",
  "example": "/wechat/tgchannel/lifeweek",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 534,
  "location": "tgchannel.ts",
  "maintainers": [
    "LogicJake",
    "Rongronggg9"
  ],
  "name": "公众号（Telegram 频道来源）",
  "parameters": {
    "id": "公众号绑定频道 id",
    "mpName": "欲筛选的公众号全名（URL-encoded，精确匹配），在频道订阅了多个公众号时可选用",
    "searchQueryType": "搜索查询类型，见下表"
  },
  "path": "/tgchannel/:id/:mpName?/:searchQueryType?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "三联生活周刊 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41372078898845696",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://t.me/s/lifeweek",
      "title": "三联生活周刊",
      "type": "feed",
      "url": "rsshub://wechat/tgchannel/lifeweek"
    },
    {
      "description": "正面连接 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41473172365329515",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://t.me/s/SubWechat",
      "title": "正面连接",
      "type": "feed",
      "url": "rsshub://wechat/tgchannel/SubWechat/%E6%AD%A3%E9%9D%A2%E8%BF%9E%E6%8E%A5/1"
    }
  ]
}
```
