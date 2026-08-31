# 全球化智库 - 动态

## Coverage
`index-only`

## Route
- Namespace: `ccg`
- Namespace Name: `全球化智库`
- Route Path: `/ccg/:category?`
- Route Name: `动态`
- Example: `/ccg/news`
- URL: `www.ccg.org.cn`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
订阅 [新闻动态](http://www.ccg.org.cn/news)，其源网址为 `http://www.ccg.org.cn/news`，请参考该 URL 指定部分构成参数，此时路由为 [`/ccg/news`](https://rsshub.app/ccg/news)。
:::

| 分类                                   | ID                                  |
| -------------------------------------- | ----------------------------------- |
| [新闻动态](http://www.ccg.org.cn/news) | [news](https://rsshub.app/ccg/news) |
| [媒体报道](http://www.ccg.org.cn/mtbd) | [mtbd](https://rsshub.app/ccg/mtbd) |

## Parameters
- `category`: {"description": "分类，默认为 `news`，即新闻动态，可在对应分类页 URL 中找到", "options": [{"label": "新闻动态", "value": "news"}, {"label": "媒体报道", "value": "mtbd"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.ccg.org.cn/category`
- `target`: `/:category`
### Rule 2
- `title`: `新闻动态`
- `source`:
  - `www.ccg.org.cn/news`
- `target`: `/news`
### Rule 3
- `title`: `媒体报道`
- `source`:
  - `www.ccg.org.cn/mtbd`
- `target`: `/mtbd`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\n订阅 [新闻动态](http://www.ccg.org.cn/news)，其源网址为 `http://www.ccg.org.cn/news`，请参考该 URL 指定部分构成参数，此时路由为 [`/ccg/news`](https://rsshub.app/ccg/news)。\n:::\n\n| 分类                                   | ID                                  |\n| -------------------------------------- | ----------------------------------- |\n| [新闻动态](http://www.ccg.org.cn/news) | [news](https://rsshub.app/ccg/news) |\n| [媒体报道](http://www.ccg.org.cn/mtbd) | [mtbd](https://rsshub.app/ccg/mtbd) |",
  "example": "/ccg/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 1,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "动态",
  "parameters": {
    "category": {
      "description": "分类，默认为 `news`，即新闻动态，可在对应分类页 URL 中找到",
      "options": [
        {
          "label": "新闻动态",
          "value": "news"
        },
        {
          "label": "媒体报道",
          "value": "mtbd"
        }
      ]
    }
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "www.ccg.org.cn/category"
      ],
      "target": "/:category"
    },
    {
      "source": [
        "www.ccg.org.cn/news"
      ],
      "target": "/news",
      "title": "新闻动态"
    },
    {
      "source": [
        "www.ccg.org.cn/mtbd"
      ],
      "target": "/mtbd",
      "title": "媒体报道"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "全球化智库 - 新闻动态 - Powered by RSSHub",
      "errorAt": "2025-11-24T21:36:21.321Z",
      "errorMessage": "[GET] \"http://www.ccg.org.cn/news\": <no response> fetch failed\n",
      "id": "200267599909362688",
      "image": "http://www.ccg.org.cn/wp-content/themes/ccg/imgs/nav-logo.png",
      "ownerUserId": null,
      "siteUrl": "http://www.ccg.org.cn/news",
      "title": "全球化智库 - 新闻动态",
      "type": "feed",
      "url": "rsshub://ccg/news"
    }
  ],
  "url": "www.ccg.org.cn",
  "view": 0
}
```
