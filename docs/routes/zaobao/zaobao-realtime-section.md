# 联合早报 - 即时新闻

## Coverage
`index-only`

## Route
- Namespace: `zaobao`
- Namespace Name: `联合早报`
- Route Path: `/zaobao/realtime/:section?`
- Route Name: `即时新闻`
- Example: `/zaobao/realtime/china`
- URL: `www.zaobao.com`
- Language: `_None_`
- Categories: `traditional-media, popular`
- Maintainers: `shunf4`
- Source Location: `realtime.ts`
- Source Module: `_None_`

## Description
| 中国  | 新加坡    | 国际  | 财经     |
| ----- | --------- | ----- | -------- |
| china | singapore | world | zfinance |

## Parameters
- `section`: 分类，缺省为 china


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "traditional-media",
    "popular"
  ],
  "description": "| 中国  | 新加坡    | 国际  | 财经     |\n| ----- | --------- | ----- | -------- |\n| china | singapore | world | zfinance |",
  "example": "/zaobao/realtime/china",
  "heat": 9146,
  "location": "realtime.ts",
  "maintainers": [
    "shunf4"
  ],
  "name": "即时新闻",
  "parameters": {
    "section": "分类，缺省为 china"
  },
  "path": "/realtime/:section?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "新加坡、中国、亚洲和国际的即时、评论、商业、体育、生活、科技与多媒体新闻，尽在联合早报。 - Powered by RSSHub",
      "errorAt": "2026-09-10T09:51:39.862Z",
      "errorMessage": "Failed query: update \"feeds\" set \"url\" = $1, \"title\" = $2, \"description\" = $3, \"site_url\" = $4, \"image\" = $5, \"checked_at\" = $6, \"refresh_enqueued_at\" = $7, \"last_modified_header\" = $8, \"etag_header\" = $9, \"ttl\" = $10, \"error_message\" = $11, \"error_at\" = $12, \"rsshub_route\" = $13, \"rsshub_namespace\" = $14 where (\"feeds\".\"id\" = $15 and (\"feeds\".\"refresh_enqueued_at\" is null or \"feeds\".\"refresh_enqueued_at\" < $16)) returning \"checked_at\"\nparams: rsshub://zaobao/realtime,《联合早报》-中港台-即时,新加坡、中国、亚洲和国际的即时、评论、商业、体育、生活、科技与多媒体新闻，尽在联合早报。 - Powered by RSSHub,https://www.zaobao.com/realtime/china,https://www.zaobao.com.sg/favicon.ico,2026-09-10T09:51:17.556Z,2026-09-10T09:50:54.491Z,Thu, 10 Sep 2026 09:51:14 GMT,W/\"e28f-81+TbpSFNvQW4HNnvxPB7Hba7Fc\",60,,,/zaobao/realtime/:section?,zaobao,67490527781761028,2026-09-10T09:50:54.491Z",
      "id": "67490527781761028",
      "image": "https://www.zaobao.com.sg/favicon.ico",
      "ownerUserId": null,
      "siteUrl": "https://www.zaobao.com/realtime/china",
      "title": "《联合早报》-中港台-即时",
      "type": "feed",
      "url": "rsshub://zaobao/realtime"
    },
    {
      "description": "新加坡、中国、亚洲和国际的即时、评论、商业、体育、生活、科技与多媒体新闻，尽在联合早报。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41461870201364483",
      "image": "https://www.zaobao.com.sg/favicon.ico",
      "ownerUserId": null,
      "siteUrl": "https://www.zaobao.com/realtime/world",
      "title": "《联合早报》-国际-即时",
      "type": "feed",
      "url": "rsshub://zaobao/realtime/world"
    }
  ]
}
```
