# 环球网 - 分类

## Coverage
`index-only`

## Route
- Namespace: `huanqiu`
- Namespace Name: `环球网`
- Route Path: `/huanqiu/news/:category?`
- Route Name: `分类`
- Example: `/huanqiu/news/china`
- URL: `huanqiu.com/`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `yuxinliu-alex`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 国内新闻 | 国际新闻 | 军事 | 台海   | 评论    |
| -------- | -------- | ---- | ------ | ------- |
| china    | world    | mil  | taiwai | opinion |

## Parameters
- `category`: 类别，可以使用二级域名作为参数，默认为：china


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
  - `huanqiu.com/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| 国内新闻 | 国际新闻 | 军事 | 台海   | 评论    |\n| -------- | -------- | ---- | ------ | ------- |\n| china    | world    | mil  | taiwai | opinion |",
  "example": "/huanqiu/news/china",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 851,
  "location": "index.ts",
  "maintainers": [
    "yuxinliu-alex"
  ],
  "name": "分类",
  "parameters": {
    "category": "类别，可以使用二级域名作为参数，默认为：china"
  },
  "path": "/news/:category?",
  "radar": [
    {
      "source": [
        "huanqiu.com/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "环球网 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59176126986620928",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://world.huanqiu.com/",
      "title": "国际新闻 - 环球网",
      "type": "feed",
      "url": "rsshub://huanqiu/news/world"
    },
    {
      "description": "环球网 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "67440517507274752",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://china.huanqiu.com/",
      "title": "国内新闻 - 环球网",
      "type": "feed",
      "url": "rsshub://huanqiu/news"
    }
  ],
  "url": "huanqiu.com/"
}
```
