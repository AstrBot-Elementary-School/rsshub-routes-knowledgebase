# 动漫之家 - 新闻站

## Coverage
`index-only`

## Route
- Namespace: `dmzj`
- Namespace Name: `动漫之家`
- Route Path: `/dmzj/news/:category?`
- Route Name: `新闻站`
- Example: `/dmzj/news/donghuaqingbao`
- URL: `news.dmzj.com/`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `vzz64`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| 漫画情报      | 轻小说情报          | 动漫周边       | 声优情报        | 音乐资讯    | 游戏资讯   | 美图欣赏      | 漫展情报       | 大杂烩  |
| ------------- | ------------------- | -------------- | --------------- | ----------- | ---------- | ------------- | -------------- | ------- |
| manhuaqingbao | qingxiaoshuoqingbao | manhuazhoubian | shengyouqingbao | yinyuezixun | youxizixun | meituxinshang | manzhanqingbao | dazahui |

## Parameters
- `category`: 类别


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `news.dmzj.com/`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "description": "| 漫画情报      | 轻小说情报          | 动漫周边       | 声优情报        | 音乐资讯    | 游戏资讯   | 美图欣赏      | 漫展情报       | 大杂烩  |\n| ------------- | ------------------- | -------------- | --------------- | ----------- | ---------- | ------------- | -------------- | ------- |\n| manhuaqingbao | qingxiaoshuoqingbao | manhuazhoubian | shengyouqingbao | yinyuezixun | youxizixun | meituxinshang | manzhanqingbao | dazahui |",
  "example": "/dmzj/news/donghuaqingbao",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 56,
  "location": "news.ts",
  "maintainers": [
    "vzz64"
  ],
  "name": "新闻站",
  "parameters": {
    "category": "类别"
  },
  "path": "/news/:category?",
  "radar": [
    {
      "source": [
        "news.dmzj.com/"
      ],
      "target": "/news"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "动画情报-动漫之家新闻站 - Powered by RSSHub",
      "errorAt": "2025-06-07T18:19:07.444Z",
      "errorMessage": "[GET] \"https://news.dmzj.com/donghuaqingbao\": <no response> fetch failed (getaddrinfo ENOTFOUND news.dmzj.com)\n[GET] \"https://news.dmzj.com/donghuaqingbao\": <no response> fetch failed (getaddrinfo ENOTFOUND news.dmzj.com)\n",
      "id": "61406402714086400",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://news.dmzj.com/donghuaqingbao",
      "title": "动画情报-动漫之家新闻站",
      "type": "feed",
      "url": "rsshub://dmzj/news/donghuaqingbao"
    },
    {
      "description": "动漫之家新闻站首页 - Powered by RSSHub",
      "errorAt": "2025-06-07T19:44:41.308Z",
      "errorMessage": "[GET] \"https://news.dmzj.com/\": <no response> fetch failed (getaddrinfo ENOTFOUND news.dmzj.com)\n",
      "id": "41467081623553024",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://news.dmzj.com/",
      "title": "动漫之家新闻站首页",
      "type": "feed",
      "url": "rsshub://dmzj/news"
    }
  ],
  "url": "news.dmzj.com/"
}
```
