# 豆瓣 - 正在上映的电影

## Coverage
`index-only`

## Route
- Namespace: `douban`
- Namespace Name: `豆瓣`
- Route Path: `/douban/movie/playing`
- Route Name: `正在上映的电影`
- Example: `/douban/movie/playing`
- URL: `www.douban.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `DIYgod`
- Source Location: `other/playing.ts`
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
_None_

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/douban/movie/playing",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 95,
  "location": "other/playing.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "正在上映的电影",
  "parameters": {},
  "path": [
    "/movie/playing",
    "/movie/playing/:score"
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "正在上映的电影 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "53908061985105932",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://movie.douban.com/cinema/nowplaying/",
      "title": "正在上映的电影",
      "type": "feed",
      "url": "rsshub://douban/movie/playing"
    }
  ]
}
```
