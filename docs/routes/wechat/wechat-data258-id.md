# 微信小程序 - 公众号（微阅读来源）

## Coverage
`index-only`

## Route
- Namespace: `wechat`
- Namespace Name: `微信小程序`
- Route Path: `/wechat/data258/:id?`
- Route Name: `公众号（微阅读来源）`
- Example: `/wechat/data258/gh_cbbad4c1d33c`
- URL: `mp.data258.com/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `Rongronggg9`
- Source Location: `data258.ts`
- Source Module: `_None_`

## Description
::: warning
由于使用了一些针对反爬的缓解措施，本路由响应较慢。默认只抓取前 5 条，可通过 `?limit=` 改变（不推荐，容易被反爬）。

该网站使用 IP 甄别访客，且应用严格的每日阅读量限额（约 15 次），请自建并确保正确配置缓存；如使用内存缓存而非 Redis 缓存，请增大缓存容量。该限额足够订阅至少 3 个公众号（假设公众号每日仅更新一次）；首页 / 分类页更新相当频繁，不推荐订阅。
:::

## Parameters
- `id`: 公众号 id 或分类 id，可在公众号页或分类页 URL 中找到；若略去，则抓取首页


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `mp.data258.com/`
  - `mp.data258.com/article/category/:id`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: warning\n由于使用了一些针对反爬的缓解措施，本路由响应较慢。默认只抓取前 5 条，可通过 `?limit=` 改变（不推荐，容易被反爬）。\n\n该网站使用 IP 甄别访客，且应用严格的每日阅读量限额（约 15 次），请自建并确保正确配置缓存；如使用内存缓存而非 Redis 缓存，请增大缓存容量。该限额足够订阅至少 3 个公众号（假设公众号每日仅更新一次）；首页 / 分类页更新相当频繁，不推荐订阅。\n:::",
  "example": "/wechat/data258/gh_cbbad4c1d33c",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "data258.ts",
  "maintainers": [
    "Rongronggg9"
  ],
  "name": "公众号（微阅读来源）",
  "parameters": {
    "id": "公众号 id 或分类 id，可在公众号页或分类页 URL 中找到；若略去，则抓取首页"
  },
  "path": "/data258/:id?",
  "radar": [
    {
      "source": [
        "mp.data258.com/",
        "mp.data258.com/article/category/:id"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [],
  "url": "mp.data258.com/"
}
```
