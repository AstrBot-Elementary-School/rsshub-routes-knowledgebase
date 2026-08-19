# 中国计算机学会 - 新闻

## Coverage
`index-only`

## Route
- Namespace: `ccf`
- Namespace Name: `中国计算机学会`
- Route Path: `/ccf/news/:category?`
- Route Name: `新闻`
- Example: `/ccf/news`
- URL: `ccf.org.cn`
- Language: `_None_`
- Categories: `study`
- Maintainers: `nczitzk`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| CCF 新闻    | CCF 聚焦 | ACM 信息  |
| ----------- | -------- | --------- |
| Media\_list | Focus    | ACM\_News |

## Parameters
- `category`: 分类，见下表，默认为 CCF 新闻


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
  - `ccf.org.cn/:category`
  - `ccf.org.cn/`
- `target`: `/news/:category`

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "description": "| CCF 新闻    | CCF 聚焦 | ACM 信息  |\n| ----------- | -------- | --------- |\n| Media\\_list | Focus    | ACM\\_News |",
  "example": "/ccf/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 20,
  "location": "news.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "新闻",
  "parameters": {
    "category": "分类，见下表，默认为 CCF 新闻"
  },
  "path": "/news/:category?",
  "radar": [
    {
      "source": [
        "ccf.org.cn/:category",
        "ccf.org.cn/"
      ],
      "target": "/news/:category"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "CCF新闻 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "61643699516131332",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.ccf.org.cn/Media_list/",
      "title": "CCF新闻",
      "type": "feed",
      "url": "rsshub://ccf/news"
    },
    {
      "description": "ACM信息 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "184150422654729217",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.ccf.org.cn/ACM_News/",
      "title": "ACM信息",
      "type": "feed",
      "url": "rsshub://ccf/news/ACM_News"
    }
  ]
}
```
