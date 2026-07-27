# 联合早报 - 新闻

## Coverage
`index-only`

## Route
- Namespace: `zaobao`
- Namespace Name: `联合早报`
- Route Path: `/zaobao/znews/:section?`
- Route Name: `新闻`
- Example: `/zaobao/znews/china`
- URL: `www.zaobao.com`
- Language: `_None_`
- Categories: `traditional-media, popular`
- Maintainers: `shunf4`
- Source Location: `znews.ts`
- Source Module: `_None_`

## Description
| 中国  | 新加坡    | 东南亚 | 国际  | 体育   |
| ----- | --------- | ------ | ----- | ------ |
| china | singapore | sea    | world | sports |

## Parameters
- `section`: 分类，缺省为 china


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
    "traditional-media",
    "popular"
  ],
  "description": "| 中国  | 新加坡    | 东南亚 | 国际  | 体育   |\n| ----- | --------- | ------ | ----- | ------ |\n| china | singapore | sea    | world | sports |",
  "example": "/zaobao/znews/china",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2087,
  "location": "znews.ts",
  "maintainers": [
    "shunf4"
  ],
  "name": "新闻",
  "parameters": {
    "section": "分类，缺省为 china"
  },
  "path": "/znews/:section?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "新加坡、中国、亚洲和国际的即时、评论、商业、体育、生活、科技与多媒体新闻，尽在联合早报。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41511702474276898",
      "image": "https://www.zaobao.com.sg/favicon.ico",
      "ownerUserId": null,
      "siteUrl": "https://www.zaobao.com/news/china",
      "title": "《联合早报》-中国-新闻",
      "type": "feed",
      "url": "rsshub://zaobao/znews/china"
    },
    {
      "description": "新加坡、中国、亚洲和国际的即时、评论、商业、体育、生活、科技与多媒体新闻，尽在联合早报。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41511702474276899",
      "image": "https://www.zaobao.com.sg/favicon.ico",
      "ownerUserId": null,
      "siteUrl": "https://www.zaobao.com/news/world",
      "title": "《联合早报》-国际-新闻",
      "type": "feed",
      "url": "rsshub://zaobao/znews/world"
    }
  ]
}
```
