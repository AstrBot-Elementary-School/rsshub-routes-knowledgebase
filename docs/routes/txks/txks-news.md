# 全国通信专业技术人员职业水平考试 - 通信考试动态

## Coverage
`index-only`

## Route
- Namespace: `txks`
- Namespace Name: `全国通信专业技术人员职业水平考试`
- Route Path: `/txks/news`
- Route Name: `通信考试动态`
- Example: `/txks/news`
- URL: `www.txks.org.cn`
- Language: `_None_`
- Categories: `study`
- Maintainers: `PrinOrange`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
**注意：** 官方网站限制了国外网络请求，可能需要通过部署在中国大陆内的 RSSHub 实例访问。

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `supportRadar`: true

## Radar
### Rule 1
- `title`: `全国通信专业技术人员职业水平考试动态`
- `source`:
  - `www.txks.org.cn/index/work`
  - `www.txks.org.cn`
  - `www.txks.org.cn/index/work.html`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "description": "**注意：** 官方网站限制了国外网络请求，可能需要通过部署在中国大陆内的 RSSHub 实例访问。",
  "example": "/txks/news",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 2,
  "location": "news.ts",
  "maintainers": [
    "PrinOrange"
  ],
  "name": "通信考试动态",
  "path": "/news",
  "radar": [
    {
      "source": [
        "www.txks.org.cn/index/work",
        "www.txks.org.cn",
        "www.txks.org.cn/index/work.html"
      ],
      "target": "/news",
      "title": "全国通信专业技术人员职业水平考试动态"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "全国通信专业技术人员职业水平考试网站最新动态和消息推送 - Powered by RSSHub",
      "errorAt": "2026-06-20T11:04:43.672Z",
      "errorMessage": "[GET] \"https://www.txks.org.cn/index/work.html\": 405 Not Allowed\n",
      "id": "105073231801801728",
      "image": "https://www.txks.org.cn/asset/image/logo/logo.png",
      "ownerUserId": null,
      "siteUrl": "https://www.txks.org.cn/index/work.html",
      "title": "全国通信专业技术人员职业水平考试",
      "type": "feed",
      "url": "rsshub://txks/news"
    }
  ]
}
```
