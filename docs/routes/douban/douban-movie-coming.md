# 豆瓣 - 电影即将上映

## Coverage
`index-only`

## Route
- Namespace: `douban`
- Namespace Name: `豆瓣`
- Route Path: `/douban/movie/coming`
- Route Name: `电影即将上映`
- Example: `/douban/movie/coming`
- URL: `www.douban.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `reonokiy`
- Source Location: `movie/coming.tsx`
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
- `title`: `豆瓣电影-即将上映`
- `source`:
  - `movie.douban.com/coming`
- `target`: `/movie/coming`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/douban/movie/coming",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 432,
  "location": "movie/coming.tsx",
  "maintainers": [
    "reonokiy"
  ],
  "name": "电影即将上映",
  "path": "/movie/coming",
  "radar": [
    {
      "source": [
        "movie.douban.com/coming"
      ],
      "target": "/movie/coming",
      "title": "豆瓣电影-即将上映"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "豆瓣电影-即将上映 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "58294482107464704",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://movie.douban.com/coming",
      "title": "豆瓣电影-即将上映",
      "type": "feed",
      "url": "rsshub://douban/movie/coming"
    }
  ]
}
```
