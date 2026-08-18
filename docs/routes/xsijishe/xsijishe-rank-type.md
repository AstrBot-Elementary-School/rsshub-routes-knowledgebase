# 司机社 - 排行榜

## Coverage
`index-only`

## Route
- Namespace: `xsijishe`
- Namespace Name: `司机社`
- Route Path: `/xsijishe/rank/:type`
- Route Name: `排行榜`
- Example: `/xsijishe/rank/weekly`
- URL: `xsijishe.com`
- Language: `_None_`
- Categories: `bbs, popular`
- Maintainers: `akynazh, AiraNadih`
- Source Location: `rank.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: {"description": "排行榜类型", "options": [{"label": "周榜", "value": "weekly"}, {"label": "月榜", "value": "monthly"}]}


## Features
- `requireConfig`: [{"description": "", "name": "XSIJISHE_COOKIE"}, {"description": "", "name": "XSIJISHE_USER_AGENT"}]
- `requirePuppeteer`: true
- `antiCrawler`: true
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
  "example": "/xsijishe/rank/weekly",
  "features": {
    "antiCrawler": true,
    "nsfw": true,
    "requireConfig": [
      {
        "description": "",
        "name": "XSIJISHE_COOKIE"
      },
      {
        "description": "",
        "name": "XSIJISHE_USER_AGENT"
      }
    ],
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 4868,
  "location": "rank.ts",
  "maintainers": [
    "akynazh",
    "AiraNadih"
  ],
  "name": "排行榜",
  "parameters": {
    "type": {
      "description": "排行榜类型",
      "options": [
        {
          "label": "周榜",
          "value": "weekly"
        },
        {
          "label": "月榜",
          "value": "monthly"
        }
      ]
    }
  },
  "path": "/rank/:type",
  "topFeeds": [
    {
      "description": "司机社综合周排行榜 - Powered by RSSHub",
      "errorAt": "2026-08-15T03:05:15.960Z",
      "errorMessage": "200 ",
      "id": "41707595233790976",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://xsijishe.com/portal.php",
      "title": "司机社综合周排行榜",
      "type": "feed",
      "url": "rsshub://xsijishe/rank/weekly"
    },
    {
      "description": "司机社综合月排行榜 - Powered by RSSHub",
      "errorAt": "2026-08-15T06:05:36.554Z",
      "errorMessage": "200 ",
      "id": "41511702474276884",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://xsijishe.com/portal.php",
      "title": "司机社综合月排行榜",
      "type": "feed",
      "url": "rsshub://xsijishe/rank/monthly"
    }
  ]
}
```
