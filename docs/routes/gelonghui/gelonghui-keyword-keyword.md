# 格隆汇 - 搜索关键字

## Coverage
`index-only`

## Route
- Namespace: `gelonghui`
- Namespace Name: `格隆汇`
- Route Path: `/gelonghui/keyword/:keyword`
- Route Name: `搜索关键字`
- Example: `/gelonghui/keyword/早报`
- URL: `gelonghui.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `keyword.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `keyword`: 搜索关键字


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
    "finance"
  ],
  "example": "/gelonghui/keyword/早报",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 110,
  "location": "keyword.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "搜索关键字",
  "parameters": {
    "keyword": "搜索关键字"
  },
  "path": "/keyword/:keyword",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "找到关于 “ 跨境电商 ”的文章，共10000个结果 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "69583577413871616",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.gelonghui.com/api/post/search/v4",
      "title": "格隆汇 - 关键词 “跨境电商” 的文章",
      "type": "feed",
      "url": "rsshub://gelonghui/keyword/%E8%B7%A8%E5%A2%83%E7%94%B5%E5%95%86"
    },
    {
      "description": "找到关于 “ 早报 ”的文章，共3467个结果 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "74277698927007744",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.gelonghui.com/api/post/search/v4",
      "title": "格隆汇 - 关键词 “早报” 的文章",
      "type": "feed",
      "url": "rsshub://gelonghui/keyword/%E6%97%A9%E6%8A%A5"
    }
  ],
  "view": 0
}
```
