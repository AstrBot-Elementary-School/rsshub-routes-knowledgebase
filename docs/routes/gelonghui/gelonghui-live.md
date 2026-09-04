# 格隆汇 - 实时快讯

## Coverage
`index-only`

## Route
- Namespace: `gelonghui`
- Namespace Name: `格隆汇`
- Route Path: `/gelonghui/live`
- Route Name: `实时快讯`
- Example: `/gelonghui/live`
- URL: `gelonghui.com/live`
- Language: `_None_`
- Categories: `finance, popular`
- Maintainers: `TonyRL`
- Source Location: `live.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `gelonghui.com/live`
  - `gelonghui.com/`

## Raw JSON
```json
{
  "categories": [
    "finance",
    "popular"
  ],
  "example": "/gelonghui/live",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1426,
  "location": "live.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "name": "实时快讯",
  "parameters": {},
  "path": "/live",
  "radar": [
    {
      "source": [
        "gelonghui.com/live",
        "gelonghui.com/"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "格隆汇快讯栏目提供外汇投资实时行情,外汇投资交易,外汇投资炒股,证券等内容,实时更新,格隆汇未来将陆续开通台湾、日本、印度、欧洲等市场. - Powered by RSSHub",
      "errorAt": "2026-09-03T08:05:37.064Z",
      "errorMessage": "Failed query: update \"feeds\" set \"url\" = $1, \"title\" = $2, \"description\" = $3, \"site_url\" = $4, \"image\" = $5, \"checked_at\" = $6, \"refresh_enqueued_at\" = $7, \"last_modified_header\" = $8, \"etag_header\" = $9, \"ttl\" = $10, \"error_message\" = $11, \"error_at\" = $12, \"rsshub_route\" = $13, \"rsshub_namespace\" = $14 where (\"feeds\".\"id\" = $15 and (\"feeds\".\"refresh_enqueued_at\" is null or \"feeds\".\"refresh_enqueued_at\" < $16)) returning \"checked_at\"\nparams: rsshub://gelonghui/live,格隆汇快讯-7x24小时市场快讯-财经市场热点,格隆汇快讯栏目提供外汇投资实时行情,外汇投资交易,外汇投资炒股,证券等内容,实时更新,格隆汇未来将陆续开通台湾、日本、印度、欧洲等市场. - Powered by RSSHub,https://www.gelonghui.com/live,https://cdn.gelonghui.com/static/web/www.ico.la.ico,2026-09-03T08:05:22.472Z,2026-09-03T08:02:24.186Z,Thu, 03 Sep 2026 08:05:15 GMT,W/\"29a3-qoWmnvlMcadTZr9PL4atWIWPheg\",60,,,/gelonghui/live,gelonghui,55611390687386624,2026-09-03T08:02:24.186Z",
      "id": "55611390687386624",
      "image": "https://cdn.gelonghui.com/static/web/www.ico.la.ico",
      "ownerUserId": null,
      "siteUrl": "https://www.gelonghui.com/live",
      "title": "格隆汇快讯-7x24小时市场快讯-财经市场热点",
      "type": "feed",
      "url": "rsshub://gelonghui/live"
    }
  ],
  "url": "gelonghui.com/live",
  "view": 0
}
```
