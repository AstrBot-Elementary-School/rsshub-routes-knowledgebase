# 豆瓣 - 豆瓣每月推荐片单

## Coverage
`index-only`

## Route
- Namespace: `douban`
- Namespace Name: `豆瓣`
- Route Path: `/douban/recommended/:type?/:routeParams?`
- Route Name: `豆瓣每月推荐片单`
- Example: `/douban/recommended/tv`
- URL: `www.douban.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `honue`
- Source Location: `other/recommended.ts`
- Source Module: `_None_`

## Description
| 额外参数 | 含义                   | 接受的值 | 默认值 |
| -------- | ---------------------- | -------- | ------ |
| playable | 仅看有可播放片源的影片 | 0/1      | 0      |
| score    | 筛选评分               | 0-10     | 0      |

用例：`/douban/recommended/tv/playable=0&score=8`

::: tip
整合了 /douban/list/ 路由，省去每月手动更新 id 参数，因为当月推荐剧集片单中，会有还未播出 / 开评分剧集、海外平台播出剧集，请自行考虑是否使用额外参数。
:::

## Parameters
- `type`: 片单类型剧集/电影，tv或movie，默认为tv
- `routeParams`: 额外参数；请参阅以下说明和表格


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
    "social-media"
  ],
  "description": "| 额外参数 | 含义                   | 接受的值 | 默认值 |\n| -------- | ---------------------- | -------- | ------ |\n| playable | 仅看有可播放片源的影片 | 0/1      | 0      |\n| score    | 筛选评分               | 0-10     | 0      |\n\n用例：`/douban/recommended/tv/playable=0&score=8`\n\n::: tip\n整合了 /douban/list/ 路由，省去每月手动更新 id 参数，因为当月推荐剧集片单中，会有还未播出 / 开评分剧集、海外平台播出剧集，请自行考虑是否使用额外参数。\n:::",
  "example": "/douban/recommended/tv",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 137,
  "location": "other/recommended.ts",
  "maintainers": [
    "honue"
  ],
  "name": "豆瓣每月推荐片单",
  "parameters": {
    "routeParams": "额外参数；请参阅以下说明和表格",
    "type": "片单类型剧集/电影，tv或movie，默认为tv"
  },
  "path": "/recommended/:type?/:routeParams?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "豆瓣 - 2026年09月定档热门新剧推荐 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "55307751412641792",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://m.douban.com/subject_collection/EC2ZBUUKA",
      "title": "豆瓣 - 2026年09月定档热门新剧推荐",
      "type": "feed",
      "url": "rsshub://douban/recommended/tv"
    },
    {
      "description": "豆瓣 - 2026年09月定档热门电影推荐 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "62747954002857984",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://m.douban.com/subject_collection/ECKZBSRSA",
      "title": "豆瓣 - 2026年09月定档热门电影推荐",
      "type": "feed",
      "url": "rsshub://douban/recommended/movie"
    }
  ]
}
```
