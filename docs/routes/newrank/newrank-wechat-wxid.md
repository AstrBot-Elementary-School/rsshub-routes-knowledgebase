# 新榜 - 微信公众号

## Coverage
`index-only`

## Route
- Namespace: `newrank`
- Namespace Name: `新榜`
- Route Path: `/newrank/wechat/:wxid`
- Route Name: `微信公众号`
- Example: `/newrank/wechat/chijiread`
- URL: `newrank.cn`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `lessmoe, pseudoyu`
- Source Location: `wechat.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `wxid`: 微信号，若微信号与新榜信息不一致，以新榜为准


## Features
- `requireConfig`: [{"description": "", "name": "NEWRANK_COOKIE"}]
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
    "social-media"
  ],
  "example": "/newrank/wechat/chijiread",
  "features": {
    "antiCrawler": true,
    "requireConfig": [
      {
        "description": "",
        "name": "NEWRANK_COOKIE"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 29,
  "location": "wechat.ts",
  "maintainers": [
    "lessmoe",
    "pseudoyu"
  ],
  "name": "微信公众号",
  "parameters": {
    "wxid": "微信号，若微信号与新榜信息不一致，以新榜为准"
  },
  "path": "/wechat/:wxid",
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-09-04T16:16:53.871Z",
      "errorMessage": "newrank RSS is disabled due to the lack of <a href=\"https://docs.rsshub.app/deploy/config#route-specific-configurations\">relevant config</a>\nnewrank RSS is disabled due to the lack of <a href=\"https://docs.rsshub.app/deploy/config#route-specific-configurations\">relevant config</a>\n",
      "id": "186422945668491336",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://newrank/wechat/chijiread"
    },
    {
      "description": null,
      "errorAt": "2025-09-04T16:16:39.569Z",
      "errorMessage": "newrank RSS is disabled due to the lack of <a href=\"https://docs.rsshub.app/deploy/config#route-specific-configurations\">relevant config</a>\n",
      "id": "186422945660102656",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://newrank/wechat/iamiBeta"
    }
  ]
}
```
