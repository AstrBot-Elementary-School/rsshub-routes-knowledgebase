# 华南理工大学 - 广州国际校区 - 通知公告

## Coverage
`index-only`

## Route
- Namespace: `scut`
- Namespace Name: `华南理工大学`
- Route Path: `/scut/gzic/notice/:category?`
- Route Name: `广州国际校区 - 通知公告`
- Example: `/scut/gzic/notice/swtz`
- URL: `jw.scut.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `gdzhht`
- Source Location: `gzic/notice.ts`
- Source Module: `_None_`

## Description
| 学术预告 | 教研通知 | 海外学习 | 事务通知 |
| -------- | -------- | -------- | -------- |
| xsyg     | jytz     | hwxx     | swtz     |

::: warning
由于学校网站对非大陆 IP 的访问存在限制，可能需自行部署。
部分通知详情页可能会被删除（返回 404），或在校园网外无法访问。
:::

## Parameters
- `category`: 通知分类，默认为 `swtz`


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 学术预告 | 教研通知 | 海外学习 | 事务通知 |\n| -------- | -------- | -------- | -------- |\n| xsyg     | jytz     | hwxx     | swtz     |\n\n::: warning\n由于学校网站对非大陆 IP 的访问存在限制，可能需自行部署。\n部分通知详情页可能会被删除（返回 404），或在校园网外无法访问。\n:::",
  "example": "/scut/gzic/notice/swtz",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 11,
  "location": "gzic/notice.ts",
  "maintainers": [
    "gdzhht"
  ],
  "name": "广州国际校区 - 通知公告",
  "parameters": {
    "category": "通知分类，默认为 `swtz`"
  },
  "path": "/gzic/notice/:category?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "华南理工大学广州国际校区 - 海外学习 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72990803507206144",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www2.scut.edu.cn/gzic/hwxx/list.htm",
      "title": "华南理工大学广州国际校区 - 海外学习",
      "type": "feed",
      "url": "rsshub://scut/gzic/notice/hwxx"
    },
    {
      "description": "华南理工大学广州国际校区 - 事务通知 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72989533354679296",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www2.scut.edu.cn/gzic/30283/list.htm",
      "title": "华南理工大学广州国际校区 - 事务通知",
      "type": "feed",
      "url": "rsshub://scut/gzic/notice/swtz"
    }
  ]
}
```
