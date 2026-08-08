# 时刻新闻 - 新闻

## Coverage
`index-only`

## Route
- Namespace: `timednews`
- Namespace Name: `时刻新闻`
- Route Path: `/timednews/news/:type?`
- Route Name: `新闻`
- Example: `/timednews/news`
- URL: `timednews.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `linbuxiao`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
子分类

| 全部 | 时政           | 财经    | 科技       | 社会   | 体娱   | 国际          | 美国 | 中国 | 欧洲   | 评论     |
| ---- | -------------- | ------- | ---------- | ------ | ------ | ------------- | ---- | ---- | ------ | -------- |
| all  | currentAffairs | finance | technology | social | sports | international | usa  | cn   | europe | comments |

## Parameters
- `type`: 子分类，见下表，默认为全部


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
    "new-media"
  ],
  "description": "子分类\n\n| 全部 | 时政           | 财经    | 科技       | 社会   | 体娱   | 国际          | 美国 | 中国 | 欧洲   | 评论     |\n| ---- | -------------- | ------- | ---------- | ------ | ------ | ------------- | ---- | ---- | ------ | -------- |\n| all  | currentAffairs | finance | technology | social | sports | international | usa  | cn   | europe | comments |",
  "example": "/timednews/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 372,
  "location": "news.ts",
  "maintainers": [
    "linbuxiao"
  ],
  "name": "新闻",
  "parameters": {
    "type": "子分类，见下表，默认为全部"
  },
  "path": "/news/:type?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "时刻新闻 全部 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "66093054954065924",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.timednews.com/topic/cat/1.html",
      "title": "时刻新闻",
      "type": "feed",
      "url": "rsshub://timednews/news"
    },
    {
      "description": "时刻新闻 全部 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "70038083495587840",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.timednews.com/topic/cat/1.html",
      "title": "时刻新闻",
      "type": "feed",
      "url": "rsshub://timednews/news/all"
    }
  ]
}
```
