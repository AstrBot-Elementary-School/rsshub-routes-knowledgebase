# 什么值得买 - 关键词

## Coverage
`index-only`

## Route
- Namespace: `smzdm`
- Namespace Name: `什么值得买`
- Route Path: `/smzdm/keyword/:keyword`
- Route Name: `关键词`
- Example: `/smzdm/keyword/女装`
- URL: `post.smzdm.com`
- Language: `_None_`
- Categories: `shopping, popular`
- Maintainers: `DIYgod, MeanZhang`
- Source Location: `keyword.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `keyword`: 你想订阅的关键词


## Features
- `requireConfig`: [{"description": "什么值得买登录后的 Cookie 值", "name": "SMZDM_COOKIE"}]
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
    "shopping",
    "popular"
  ],
  "example": "/smzdm/keyword/女装",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "什么值得买登录后的 Cookie 值",
        "name": "SMZDM_COOKIE"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 4600,
  "location": "keyword.ts",
  "maintainers": [
    "DIYgod",
    "MeanZhang"
  ],
  "name": "关键词",
  "parameters": {
    "keyword": "你想订阅的关键词"
  },
  "path": "/keyword/:keyword",
  "topFeeds": [
    {
      "description": "历史低价 - 什么值得买 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "56173305095094272",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://search.smzdm.com/?c=home&s=%E5%8E%86%E5%8F%B2%E4%BD%8E%E4%BB%B7&order=time",
      "title": "历史低价 - 什么值得买",
      "type": "feed",
      "url": "rsshub://smzdm/keyword/%E5%8E%86%E5%8F%B2%E4%BD%8E%E4%BB%B7"
    },
    {
      "description": "绝对值 - 什么值得买 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "56874574824669184",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://search.smzdm.com/?c=home&s=%E7%BB%9D%E5%AF%B9%E5%80%BC&order=time",
      "title": "绝对值 - 什么值得买",
      "type": "feed",
      "url": "rsshub://smzdm/keyword/%E7%BB%9D%E5%AF%B9%E5%80%BC"
    }
  ],
  "view": 5
}
```
