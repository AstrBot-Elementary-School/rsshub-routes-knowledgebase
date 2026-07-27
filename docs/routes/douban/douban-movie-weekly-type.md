# 豆瓣 - 一周口碑榜

## Coverage
`index-only`

## Route
- Namespace: `douban`
- Namespace Name: `豆瓣`
- Route Path: `/douban/movie/weekly/:type?`
- Route Name: `一周口碑榜`
- Example: `/douban/movie/weekly`
- URL: `www.douban.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `numm233, nczitzk`
- Source Location: `other/weekly-best.tsx`
- Source Module: `_None_`

## Description
| 一周口碑电影榜      | 华语口碑剧集榜            |
| ------------------- | ------------------------- |
| movie\_weekly\_best | tv\_chinese\_best\_weekly |

## Parameters
- `type`: 分类，可在榜单页 URL 中找到，默认为一周口碑电影榜


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
  "description": "| 一周口碑电影榜      | 华语口碑剧集榜            |\n| ------------------- | ------------------------- |\n| movie\\_weekly\\_best | tv\\_chinese\\_best\\_weekly |",
  "example": "/douban/movie/weekly",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 473,
  "location": "other/weekly-best.tsx",
  "maintainers": [
    "numm233",
    "nczitzk"
  ],
  "name": "一周口碑榜",
  "parameters": {
    "type": "分类，可在榜单页 URL 中找到，默认为一周口碑电影榜"
  },
  "path": "/movie/weekly/:type?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "每周五更新；关注榜单，第一时间了解最新口碑佳片。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "48039983835900997",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://m.douban.com/subject_collection/movie_weekly_best",
      "title": "一周口碑电影榜",
      "type": "feed",
      "url": "rsshub://douban/movie/weekly"
    },
    {
      "description": "每周三更新；关注榜单，第一时间了解最新华语口碑好剧。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "69962972966865920",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://m.douban.com/subject_collection/tv_chinese_best_weekly",
      "title": "华语口碑剧集榜",
      "type": "feed",
      "url": "rsshub://douban/movie/weekly/tv_chinese_best_weekly"
    }
  ]
}
```
