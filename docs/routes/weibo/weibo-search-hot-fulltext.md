# 微博 - 热搜榜

## Coverage
`index-only`

## Route
- Namespace: `weibo`
- Namespace Name: `微博`
- Route Path: `/weibo/search/hot/:fulltext?`
- Route Name: `热搜榜`
- Example: `/weibo/search/hot`
- URL: `s.weibo.com/top/summary`
- Language: `_None_`
- Categories: `social-media, popular`
- Maintainers: `xyqfer, shinemoon`
- Source Location: `search/hot.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `fulltext`: {"description": "\n-   使用`/weibo/search/hot`可以获取热搜条目列表；\n-   使用`/weibo/search/hot/fulltext`可以进一步获取热搜条目下的摘要信息（不含图片视频）；\n-   使用`/weibo/search/hot/fulltext?pic=true`可以获取图片缩略（但需要配合额外的手段，例如浏览器上的 Header Editor 等来修改 referer 参数为`https://weibo.com`，以规避微博的外链限制，否则图片无法显示。）\n-   使用`/weibo/search/hot/fulltext?pic=true&fullpic=true`可以获取 Original 图片（但需要配合额外的手段，例如浏览器上的 Header Editor 等来修改 referer 参数为`https://weibo.com`，以规避微博的外链限制，否则图片无法显示。）"}


## Features
- `requireConfig`: [{"description": "", "name": "WEIBO_COOKIES", "optional": true}]
- `requirePuppeteer`: true
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `s.weibo.com/top/summary`

## Raw JSON
```json
{
  "categories": [
    "social-media",
    "popular"
  ],
  "example": "/weibo/search/hot",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "",
        "name": "WEIBO_COOKIES",
        "optional": true
      }
    ],
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 6852,
  "location": "search/hot.tsx",
  "maintainers": [
    "xyqfer",
    "shinemoon"
  ],
  "name": "热搜榜",
  "parameters": {
    "fulltext": {
      "description": "\n-   使用`/weibo/search/hot`可以获取热搜条目列表；\n-   使用`/weibo/search/hot/fulltext`可以进一步获取热搜条目下的摘要信息（不含图片视频）；\n-   使用`/weibo/search/hot/fulltext?pic=true`可以获取图片缩略（但需要配合额外的手段，例如浏览器上的 Header Editor 等来修改 referer 参数为`https://weibo.com`，以规避微博的外链限制，否则图片无法显示。）\n-   使用`/weibo/search/hot/fulltext?pic=true&fullpic=true`可以获取 Original 图片（但需要配合额外的手段，例如浏览器上的 Header Editor 等来修改 referer 参数为`https://weibo.com`，以规避微博的外链限制，否则图片无法显示。）"
    }
  },
  "path": "/search/hot/:fulltext?",
  "radar": [
    {
      "source": [
        "s.weibo.com/top/summary"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "实时热点，每分钟更新一次 - Powered by RSSHub",
      "errorAt": "2026-09-09T08:56:23.406Z",
      "errorMessage": "Failed query: update \"feeds\" set \"url\" = $1, \"title\" = $2, \"description\" = $3, \"site_url\" = $4, \"checked_at\" = $5, \"refresh_enqueued_at\" = $6, \"last_modified_header\" = $7, \"etag_header\" = $8, \"ttl\" = $9, \"error_message\" = $10, \"error_at\" = $11, \"rsshub_route\" = $12, \"rsshub_namespace\" = $13 where (\"feeds\".\"id\" = $14 and (\"feeds\".\"refresh_enqueued_at\" is null or \"feeds\".\"refresh_enqueued_at\" < $15)) returning \"checked_at\"\nparams: rsshub://weibo/search/hot,微博热搜榜,实时热点，每分钟更新一次 - Powered by RSSHub,https://s.weibo.com/top/summary?cate=realtimehot,2026-09-09T08:56:07.038Z,2026-09-09T08:53:27.461Z,Wed, 09 Sep 2026 08:55:57 GMT,W/\"339e-miruMco3km5Qvtf228Ron+LunVc\",60,,,/weibo/search/hot/:fulltext?,weibo,41358830592746496,2026-09-09T08:53:27.461Z",
      "id": "41358830592746496",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://s.weibo.com/top/summary?cate=realtimehot",
      "title": "微博热搜榜",
      "type": "feed",
      "url": "rsshub://weibo/search/hot"
    },
    {
      "description": "实时热点，每分钟更新一次 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "57266422630121472",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://s.weibo.com/top/summary?cate=realtimehot",
      "title": "微博热搜榜",
      "type": "feed",
      "url": "rsshub://weibo/search/hot/fulltext"
    }
  ],
  "url": "s.weibo.com/top/summary",
  "view": 1
}
```
