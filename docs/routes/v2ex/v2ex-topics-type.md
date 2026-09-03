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
  "heat": 23592,
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
      "errorAt": "2026-09-02T09:34:43.579Z",
      "errorMessage": "Failed query: update \"feeds\" set \"url\" = $1, \"title\" = $2, \"description\" = $3, \"site_url\" = $4, \"checked_at\" = $5, \"refresh_enqueued_at\" = $6, \"last_modified_header\" = $7, \"etag_header\" = $8, \"ttl\" = $9, \"error_message\" = $10, \"error_at\" = $11, \"rsshub_route\" = $12, \"rsshub_namespace\" = $13 where (\"feeds\".\"id\" = $14 and (\"feeds\".\"refresh_enqueued_at\" is null or \"feeds\".\"refresh_enqueued_at\" < $15)) returning \"checked_at\"\nparams: rsshub://v2ex/topics/latest,V2EX-最新主题,V2EX-最新主题 - Powered by RSSHub,https://www.v2ex.com/,2026-09-02T09:34:29.998Z,2026-09-02T09:34:02.232Z,Wed, 02 Sep 2026 09:34:21 GMT,W/\"3d651-Izd4E1mMnisATFVXrbPkEO4YU8c\",60,,,/v2ex/topics/:type,v2ex,41374278075966464,2026-09-02T09:34:02.232Z",
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
