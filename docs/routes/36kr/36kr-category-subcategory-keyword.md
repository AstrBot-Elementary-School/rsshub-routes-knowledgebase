# 36kr - 资讯, 快讯, 用户文章, 主题文章, 专题文章, 搜索文章, 搜索快讯

## Coverage
`index-only`

## Route
- Namespace: `36kr`
- Namespace Name: `36kr`
- Route Path: `/36kr/:category/:subCategory?/:keyword?`
- Route Name: `资讯, 快讯, 用户文章, 主题文章, 专题文章, 搜索文章, 搜索快讯`
- Example: `/36kr/newsflashes`
- URL: `36kr.com`
- Language: `_None_`
- Categories: `new-media, popular`
- Maintainers: `nczitzk, fashioncj`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 最新资讯频道 | 快讯        | 推荐资讯  | 生活 | 房产   | 职场      | 搜索文章                | 搜索快讯                |
| ------------ | ----------- | --------- | ---- | ------ | --------- | ----------------------- | ----------------------- |
| news         | newsflashes | recommend | life | estate | workplace | search/articles/ 关键词 | search/articles/ 关键词 |

## Parameters
- `category`: 分类，必填项
- `subCategory`: 子分类，选填项，目的是为了兼容老逻辑
- `keyword`: 关键词，选填项，仅搜索文章/快讯时有效


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media",
    "popular"
  ],
  "description": "| 最新资讯频道 | 快讯        | 推荐资讯  | 生活 | 房产   | 职场      | 搜索文章                | 搜索快讯                |\n| ------------ | ----------- | --------- | ---- | ------ | --------- | ----------------------- | ----------------------- |\n| news         | newsflashes | recommend | life | estate | workplace | search/articles/ 关键词 | search/articles/ 关键词 |",
  "example": "/36kr/newsflashes",
  "heat": 2513,
  "location": "index.ts",
  "maintainers": [
    "nczitzk",
    "fashioncj"
  ],
  "name": "资讯, 快讯, 用户文章, 主题文章, 专题文章, 搜索文章, 搜索快讯",
  "parameters": {
    "category": "分类，必填项",
    "keyword": "关键词，选填项，仅搜索文章/快讯时有效",
    "subCategory": "子分类，选填项，目的是为了兼容老逻辑"
  },
  "path": "/:category/:subCategory?/:keyword?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "36氪 - 快讯 - Powered by RSSHub",
      "errorAt": "2026-09-11T09:04:41.925Z",
      "errorMessage": "Failed query: update \"feeds\" set \"url\" = $1, \"title\" = $2, \"description\" = $3, \"site_url\" = $4, \"checked_at\" = $5, \"refresh_enqueued_at\" = $6, \"last_modified_header\" = $7, \"etag_header\" = $8, \"ttl\" = $9, \"error_message\" = $10, \"error_at\" = $11, \"rsshub_route\" = $12, \"rsshub_namespace\" = $13 where (\"feeds\".\"id\" = $14 and (\"feeds\".\"refresh_enqueued_at\" is null or \"feeds\".\"refresh_enqueued_at\" < $15)) returning \"checked_at\"\nparams: rsshub://36kr/newsflashes,36氪 - 快讯,36氪 - 快讯 - Powered by RSSHub,https://www.36kr.com/newsflashes,2026-09-11T09:04:34.691Z,2026-09-11T09:04:24.773Z,Fri, 11 Sep 2026 09:04:27 GMT,W/\"2ccf-cp8Z9IupmBoj1n/+ZBjLQDnxy/8\",60,,,/36kr/:category/:subCategory?/:keyword?,36kr,41572238273905665,2026-09-11T09:04:24.773Z",
      "id": "41572238273905665",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.36kr.com/newsflashes",
      "title": "36氪 - 快讯",
      "type": "feed",
      "url": "rsshub://36kr/newsflashes"
    },
    {
      "description": "36氪 - 最新资讯频道 - Powered by RSSHub",
      "errorAt": "2026-08-06T00:32:51.823Z",
      "errorMessage": "Cannot read properties of null (reading '1')\n502 \nCannot read properties of null (reading '1')\nCannot read properties of null (reading '1')\n",
      "id": "66129443815812096",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.36kr.com/information/web_news",
      "title": "36氪 - 最新资讯频道",
      "type": "feed",
      "url": "rsshub://36kr/news"
    }
  ]
}
```
