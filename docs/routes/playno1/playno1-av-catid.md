# PLAYNO.1 玩樂達人 - AV

## Coverage
`index-only`

## Route
- Namespace: `playno1`
- Namespace Name: `PLAYNO.1 玩樂達人`
- Route Path: `/playno1/av/:catid?`
- Route Name: `AV`
- Example: `/playno1/av`
- URL: `stno1.playno1.com`
- Language: `_None_`
- Categories: `bbs, popular`
- Maintainers: `TonyRL`
- Source Location: `av.ts`
- Source Module: `_None_`

## Description
::: warning
目前观测到该博客可能禁止日本 IP 访问。建议部署在日本区以外的服务器上。
:::

| 全部文章 | AV 新聞 | AV 導覽 |
| -------- | ------- | ------- |
| 78       | 3       | 5       |

## Parameters
- `catid`: 分类，见下表，默认为全部文章


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "bbs",
    "popular"
  ],
  "description": "::: warning\n目前观测到该博客可能禁止日本 IP 访问。建议部署在日本区以外的服务器上。\n:::\n\n| 全部文章 | AV 新聞 | AV 導覽 |\n| -------- | ------- | ------- |\n| 78       | 3       | 5       |",
  "example": "/playno1/av",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1707,
  "location": "av.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "AV",
  "parameters": {
    "catid": "分类，见下表，默认为全部文章"
  },
  "path": "/av/:catid?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "全部文章-AVNo.1-PLAYNO.1玩樂達人 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41511702474276873",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.playno1.com/portal.php?mod=list&catid=78",
      "title": "全部文章-AVNo.1-PLAYNO.1玩樂達人",
      "type": "feed",
      "url": "rsshub://playno1/av"
    },
    {
      "description": "新聞-AVNo.1-PLAYNO.1玩樂達人 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "55955399997421568",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.playno1.com/portal.php?mod=list&catid=3",
      "title": "新聞-AVNo.1-PLAYNO.1玩樂達人",
      "type": "feed",
      "url": "rsshub://playno1/av/3"
    }
  ]
}
```
