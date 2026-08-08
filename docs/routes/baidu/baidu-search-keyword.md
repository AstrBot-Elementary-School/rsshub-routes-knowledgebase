# 百度 - 搜索

## Coverage
`index-only`

## Route
- Namespace: `baidu`
- Namespace Name: `百度`
- Route Path: `/baidu/search/:keyword`
- Route Name: `搜索`
- Example: `/baidu/search/rss`
- URL: `www.baidu.com`
- Language: `_None_`
- Categories: `other`
- Maintainers: `CaoMeiYouRen`
- Source Location: `search.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `keyword`: 搜索关键词


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/baidu/search/rss",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 7,
  "location": "search.tsx",
  "maintainers": [
    "CaoMeiYouRen"
  ],
  "name": "搜索",
  "parameters": {
    "keyword": "搜索关键词"
  },
  "path": "/search/:keyword",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "广州教师 - 百度搜索 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "177651896288583683",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.baidu.com/s?wd=%E5%B9%BF%E5%B7%9E%E6%95%99%E5%B8%88",
      "title": "广州教师 - 百度搜索",
      "type": "feed",
      "url": "rsshub://baidu/search/%E5%B9%BF%E5%B7%9E%E6%95%99%E5%B8%88"
    },
    {
      "description": "符号学 - 百度搜索 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "177651896288583681",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.baidu.com/s?wd=%E7%AC%A6%E5%8F%B7%E5%AD%A6",
      "title": "符号学 - 百度搜索",
      "type": "feed",
      "url": "rsshub://baidu/search/%E7%AC%A6%E5%8F%B7%E5%AD%A6"
    }
  ]
}
```
