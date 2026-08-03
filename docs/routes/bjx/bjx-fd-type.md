# 北极星电力网 - 风电

## Coverage
`index-only`

## Route
- Namespace: `bjx`
- Namespace Name: `北极星电力网`
- Route Path: `/bjx/fd/:type`
- Route Name: `风电`
- Example: `/bjx/fd/yw`
- URL: `www.bjx.com.cn`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `hualiong`
- Source Location: `fd.ts`
- Source Module: `_None_`

## Description
`:type` 类型可选如下

| 要闻 | 政策 | 数据 | 市场 | 企业 | 招标 | 技术 | 报道 |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| yw   | zc   | sj   | sc   | mq   | zb   | js   | bd   |

## Parameters
- `type`: 文章分类，详见下表


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
    "traditional-media"
  ],
  "description": "`:type` 类型可选如下\n\n| 要闻 | 政策 | 数据 | 市场 | 企业 | 招标 | 技术 | 报道 |\n| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |\n| yw   | zc   | sj   | sc   | mq   | zb   | js   | bd   |",
  "example": "/bjx/fd/yw",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 10,
  "location": "fd.ts",
  "maintainers": [
    "hualiong"
  ],
  "name": "风电",
  "parameters": {
    "type": "文章分类，详见下表"
  },
  "path": "/fd/:type",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "北极星风力发电网要闻 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "74275326708265984",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://fd.bjx.com.cn/yw/",
      "title": "北极星风力发电网要闻",
      "type": "feed",
      "url": "rsshub://bjx/fd/yw"
    },
    {
      "description": "北极星风力发电网政策 - Powered by RSSHub",
      "errorAt": "2025-10-11T06:37:27.894Z",
      "errorMessage": "Failed to fetch\n",
      "id": "150031434100937728",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://fd.bjx.com.cn/zc/",
      "title": "北极星风力发电网政策",
      "type": "feed",
      "url": "rsshub://bjx/fd/zc"
    }
  ]
}
```
