# V2EX - 最热 / 最新主题

## Coverage
`index-only`

## Route
- Namespace: `v2ex`
- Namespace Name: `V2EX`
- Route Path: `/v2ex/topics/:type`
- Route Name: `最热 / 最新主题`
- Example: `/v2ex/topics/latest`
- URL: `v2ex.com`
- Language: `_None_`
- Categories: `bbs, popular`
- Maintainers: `WhiteWorld`
- Source Location: `topics.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: {"default": "hot", "description": "主题类型", "options": [{"label": "最热主题", "value": "hot"}, {"label": "最新主题", "value": "latest"}]}


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
    "bbs",
    "popular"
  ],
  "example": "/v2ex/topics/latest",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 23528,
  "location": "topics.ts",
  "maintainers": [
    "WhiteWorld"
  ],
  "name": "最热 / 最新主题",
  "parameters": {
    "type": {
      "default": "hot",
      "description": "主题类型",
      "options": [
        {
          "label": "最热主题",
          "value": "hot"
        },
        {
          "label": "最新主题",
          "value": "latest"
        }
      ]
    }
  },
  "path": "/topics/:type",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "V2EX-最热主题 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41147805268337669",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.v2ex.com/",
      "title": "V2EX-最热主题",
      "type": "feed",
      "url": "rsshub://v2ex/topics/hot"
    },
    {
      "description": "V2EX-最新主题 - Powered by RSSHub",
      "errorAt": "2026-08-03T06:06:50.513Z",
      "errorMessage": "Failed query: select \"subscriptions\".\"user_id\", \"rsshub_usage\".\"rsshub_id\", \"rsshub\".\"base_url\", \"rsshub\".\"access_key\", \"rsshub\".\"error_message\" from \"subscriptions\" left join \"rsshub_usage\" on \"subscriptions\".\"user_id\" = \"rsshub_usage\".\"user_id\" left join \"rsshub\" on \"rsshub\".\"id\" = \"rsshub_usage\".\"rsshub_id\" where \"subscriptions\".\"feed_id\" = $1\nparams: 41374278075966464",
      "id": "41374278075966464",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.v2ex.com/",
      "title": "V2EX-最新主题",
      "type": "feed",
      "url": "rsshub://v2ex/topics/latest"
    }
  ],
  "view": 0
}
```
