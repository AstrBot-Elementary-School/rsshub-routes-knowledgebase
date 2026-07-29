# 逛丢 - 关键字搜索

## Coverage
`index-only`

## Route
- Namespace: `guangdiu`
- Namespace Name: `逛丢`
- Route Path: `/guangdiu/search/:query?`
- Route Name: `关键字搜索`
- Example: `/guangdiu/search/q=百度网盘`
- URL: `guangdiu.com`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `Huzhixin00`
- Source Location: `search.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `query`: 链接参数，对应网址问号后的内容


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
    "shopping"
  ],
  "example": "/guangdiu/search/q=百度网盘",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 12,
  "location": "search.ts",
  "maintainers": [
    "Huzhixin00"
  ],
  "name": "关键字搜索",
  "parameters": {
    "query": "链接参数，对应网址问号后的内容"
  },
  "path": "/search/:query?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "逛丢 - 今日必买 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "141468238742304768",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://guangdiu.com/search.php?q=%E4%BB%8A%E6%97%A5%E5%BF%85%E4%B9%B0",
      "title": "逛丢 - 今日必买",
      "type": "feed",
      "url": "rsshub://guangdiu/search/q=%E4%BB%8A%E6%97%A5%E5%BF%85%E4%B9%B0"
    },
    {
      "description": "逛丢 - 6750gre - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "136052350296282112",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://guangdiu.com/search.php?q=6750gre",
      "title": "逛丢 - 6750gre",
      "type": "feed",
      "url": "rsshub://guangdiu/search/q=6750gre"
    }
  ]
}
```
