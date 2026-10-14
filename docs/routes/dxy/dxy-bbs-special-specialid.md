# 丁香园 - 专题

## Coverage
`index-only`

## Route
- Namespace: `dxy`
- Namespace Name: `丁香园`
- Route Path: `/dxy/bbs/special/:specialId`
- Route Name: `专题`
- Example: `/dxy/bbs/special/72`
- URL: `dxy.cn`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `TonyRL`
- Source Location: `special.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `specialId`: 专题 ID，可在对应专题页 URL 中找到


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
    "bbs"
  ],
  "example": "/dxy/bbs/special/72",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 5,
  "location": "special.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "专题",
  "parameters": {
    "specialId": "专题 ID，可在对应专题页 URL 中找到"
  },
  "path": "/bbs/special/:specialId",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "汇集用药争议及药物不良反应讨论 11 內容 13297 关注 - Powered by RSSHub",
      "errorAt": "2025-08-12T09:03:45.206Z",
      "errorMessage": "请求方法不存在\n请求方法不存在\n",
      "id": "95022085506695168",
      "image": "https://img1.dxycdn.com/2020/0103/377/3388803871039625525-2.png",
      "ownerUserId": null,
      "siteUrl": "https://3g.dxy.cn/bbs/special?specialId=117",
      "title": "临床用药热议",
      "type": "feed",
      "url": "rsshub://dxy/bbs/special/117"
    }
  ]
}
```
