# 知乎 - 知乎热榜

## Coverage
`index-only`

## Route
- Namespace: `zhihu`
- Namespace Name: `知乎`
- Route Path: `/zhihu/hot/:category?`
- Route Name: `知乎热榜`
- Example: `/zhihu/hot`
- URL: `www.zhihu.com`
- Language: `_None_`
- Categories: `social-media, popular`
- Maintainers: `nczitzk, pseudoyu, DIYgod`
- Source Location: `hot.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: [{"description": "", "name": "ZHIHU_COOKIES", "optional": true}]
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
    "social-media",
    "popular"
  ],
  "example": "/zhihu/hot",
  "features": {
    "antiCrawler": true,
    "requireConfig": [
      {
        "description": "",
        "name": "ZHIHU_COOKIES",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 15713,
  "location": "hot.ts",
  "maintainers": [
    "nczitzk",
    "pseudoyu",
    "DIYgod"
  ],
  "name": "知乎热榜",
  "path": "/hot/:category?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "知乎热榜 - Powered by RSSHub",
      "errorAt": "2026-09-28T13:36:07.434Z",
      "errorMessage": "Failed query: update \"feeds\" set \"url\" = $1, \"title\" = $2, \"description\" = $3, \"site_url\" = $4, \"checked_at\" = $5, \"refresh_enqueued_at\" = $6, \"last_modified_header\" = $7, \"etag_header\" = $8, \"ttl\" = $9, \"error_message\" = $10, \"error_at\" = $11, \"rsshub_route\" = $12, \"rsshub_namespace\" = $13 where (\"feeds\".\"id\" = $14 and (\"feeds\".\"refresh_enqueued_at\" is null or \"feeds\".\"refresh_enqueued_at\" < $15)) returning \"checked_at\"\nparams: rsshub://zhihu/hot,知乎热榜,知乎热榜 - Powered by RSSHub,https://www.zhihu.com/hot,2026-09-28T13:35:35.363Z,2026-09-28T13:35:22.097Z,Mon, 28 Sep 2026 13:35:33 GMT,W/\"727d-2onRYKj7EKhlCb+8hvMC2HwGPbc\",60,,,/zhihu/hot/:category?,zhihu,41358761177015296,2026-09-28T13:35:22.097Z",
      "id": "41358761177015296",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.zhihu.com/hot",
      "title": "知乎热榜",
      "type": "feed",
      "url": "rsshub://zhihu/hot"
    }
  ],
  "view": 0
}
```
