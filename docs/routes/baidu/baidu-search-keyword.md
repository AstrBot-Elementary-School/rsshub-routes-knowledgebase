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
      "description": "罗源 新闻&oq=罗源 新闻&rsv_pq=87e4d4de002132b7&rsv_t=17e00LA1HanVp7Pv33dkIizci6Ej6zyjhAhPYV+jjrC8YXa2Vq+kkYMiUgs&rqlang=cn&rsv_enter=1&rsv_dl=tb&gpc=stf=1712564688,1715243088|stftype=1&tfflag=1 - 百度搜索 - Powered by RSSHub",
      "errorAt": "2025-09-26T13:35:14.645Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "72177058129713152",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.baidu.com/s?wd=%E7%BD%97%E6%BA%90%20%E6%96%B0%E9%97%BB%26oq%3D%E7%BD%97%E6%BA%90%20%E6%96%B0%E9%97%BB%26rsv_pq%3D87e4d4de002132b7%26rsv_t%3D17e00LA1HanVp7Pv33dkIizci6Ej6zyjhAhPYV%2BjjrC8YXa2Vq%2BkkYMiUgs%26rqlang%3Dcn%26rsv_enter%3D1%26rsv_dl%3Dtb%26gpc%3Dstf%3D1712564688%2C1715243088%7Cstftype%3D1%26tfflag%3D1",
      "title": "罗源 新闻&oq=罗源 新闻&rsv_pq=87e4d4de002132b7&rsv_t=17e00LA1HanVp7Pv33dkIizci6Ej6zyjhAhPYV+jjrC8YXa2Vq+kkYMiUgs&rqlang=cn&rsv_enter=1&rsv_dl=tb&gpc=stf=1712564688,1715243088|stftype=1&tfflag=1 - 百度搜索",
      "type": "feed",
      "url": "rsshub://baidu/search/%E7%BD%97%E6%BA%90%20%E6%96%B0%E9%97%BB&oq=%E7%BD%97%E6%BA%90%20%E6%96%B0%E9%97%BB&rsv_pq=87e4d4de002132b7&rsv_t=17e00LA1HanVp7Pv33dkIizci6Ej6zyjhAhPYV%2BjjrC8YXa2Vq%2BkkYMiUgs&rqlang=cn&rsv_enter=1&rsv_dl=tb&gpc=stf%3D1712564688%2C1715243088%7Cstftype%3D1&tfflag=1"
    },
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
    }
  ]
}
```
