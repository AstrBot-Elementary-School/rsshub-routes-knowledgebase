# 豆瓣 - 电影分类

## Coverage
`index-only`

## Route
- Namespace: `douban`
- Namespace Name: `豆瓣`
- Route Path: `/douban/movie/classification/:sort?/:score?/:tags?`
- Route Name: `电影分类`
- Example: `/douban/movie/classification/R/6/Netflix,2020`
- URL: `www.douban.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `zzwab`
- Source Location: `other/classification.ts`
- Source Module: `_None_`

## Description
排序方式可选值如下

| 近期热门 | 标记最多 | 评分最高 | 最近上映 |
| -------- | -------- | -------- | -------- |
| U        | T        | S        | R        |

## Parameters
- `sort`: 排序方式，默认为U
- `score`: 最低评分，默认不限制
- `tags`: 分类标签，多个标签之间用英文逗号分隔，常见的标签到豆瓣电影的分类页面查看，支持自定义标签


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
  "description": "排序方式可选值如下\n\n| 近期热门 | 标记最多 | 评分最高 | 最近上映 |\n| -------- | -------- | -------- | -------- |\n| U        | T        | S        | R        |",
  "example": "/douban/movie/classification/R/6/Netflix,2020",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 26,
  "location": "other/classification.ts",
  "maintainers": [
    "zzwab"
  ],
  "name": "电影分类",
  "parameters": {
    "score": "最低评分，默认不限制",
    "sort": "排序方式，默认为U",
    "tags": "分类标签，多个标签之间用英文逗号分隔，常见的标签到豆瓣电影的分类页面查看，支持自定义标签"
  },
  "path": "/movie/classification/:sort?/:score?/:tags?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "豆瓣电影分类超过 7.5 分的影视 - Powered by RSSHub",
      "errorAt": "2026-10-14T09:20:42.822Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "64117673690336325",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://movie.douban.com/tag/#/?sort=U&range=0,10&tags=",
      "title": "豆瓣电影分类超过 7.5 分的影视",
      "type": "feed",
      "url": "rsshub://douban/movie/classification/R/7.5/%25E7%25A7%2591%25E5%25B9%25BB"
    },
    {
      "description": "豆瓣电影分类影视 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "155307226993530880",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://movie.douban.com/tag/#/?sort=U&range=0,10&tags=",
      "title": "豆瓣电影分类影视",
      "type": "feed",
      "url": "rsshub://douban/movie/classification"
    }
  ]
}
```
