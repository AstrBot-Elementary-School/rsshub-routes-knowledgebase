# The Wall Street Journal (WSJ) 华尔街日报 - News

## Coverage
`index-only`

## Route
- Namespace: `wsj`
- Namespace Name: `The Wall Street Journal (WSJ) 华尔街日报`
- Route Path: `/wsj/:lang/:category?`
- Route Name: `News`
- Example: `/wsj/en-us/opinion`
- URL: `cn.wsj.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `oppilate`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
en\_us

| World | U.S. | Politics | Economy | Business | Tech       | Markets | Opinion | Books & Arts | Real Estate | Life & Work | Sytle               | Sports |
| ----- | ---- | -------- | ------- | -------- | ---------- | ------- | ------- | ------------ | ----------- | ----------- | ------------------- | ------ |
| world | us   | politics | economy | business | technology | markets | opinion | books-arts   | realestate  | life-work   | style-entertainment | sports |

zh-cn / zh-tw

| 国际  | 中国  | 金融市场 | 经济    | 商业     | 科技       | 派        | 专栏与观点 |
| ----- | ----- | -------- | ------- | -------- | ---------- | --------- | ---------- |
| world | china | markets  | economy | business | technology | life-arts | opinion    |

Provide full article RSS for WSJ topics.

## Parameters
- `lang`: Language, `en-us`, `zh-cn`, `zh-tw`
- `category`: Category. See below


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
    "traditional-media"
  ],
  "description": "en\\_us\n\n| World | U.S. | Politics | Economy | Business | Tech       | Markets | Opinion | Books & Arts | Real Estate | Life & Work | Sytle               | Sports |\n| ----- | ---- | -------- | ------- | -------- | ---------- | ------- | ------- | ------------ | ----------- | ----------- | ------------------- | ------ |\n| world | us   | politics | economy | business | technology | markets | opinion | books-arts   | realestate  | life-work   | style-entertainment | sports |\n\nzh-cn / zh-tw\n\n| 国际  | 中国  | 金融市场 | 经济    | 商业     | 科技       | 派        | 专栏与观点 |\n| ----- | ----- | -------- | ------- | -------- | ---------- | --------- | ---------- |\n| world | china | markets  | economy | business | technology | life-arts | opinion    |\n\nProvide full article RSS for WSJ topics.",
  "example": "/wsj/en-us/opinion",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 115,
  "location": "news.ts",
  "maintainers": [
    "oppilate"
  ],
  "name": "News",
  "parameters": {
    "category": "Category. See below",
    "lang": "Language, `en-us`, `zh-cn`, `zh-tw`"
  },
  "path": "/:lang/:category?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-05-30T05:50:59.428Z",
      "errorMessage": "[GET] \"https://cn.wsj.com/zh-hans\": 401 \nCannot read properties of null (reading '0')\n",
      "id": "151150448547738625",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://wsj/zh-cn"
    },
    {
      "description": null,
      "errorAt": "2025-05-29T11:39:04.736Z",
      "errorMessage": "[GET] \"https://cn.wsj.com/zh-hans/news/opinion\": 401 HTTP Forbidden\n",
      "id": "150876888307287071",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://wsj/zh-cn/opinion"
    }
  ]
}
```
