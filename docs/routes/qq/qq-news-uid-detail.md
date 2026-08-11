# 腾讯网 - 用户主页列表

## Coverage
`index-only`

## Route
- Namespace: `qq`
- Namespace Name: `腾讯网`
- Route Path: `/qq/news/:uid/:detail?`
- Route Name: `用户主页列表`
- Example: `/qq/news/8QMZ2X5a5YUeujw=`
- URL: `qq.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `hualiong`
- Source Location: `news/user.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `uid`: 用户 ID, 用户主页 URL 中的最后一段部分
- `detail`: 是否抓取全文，该值只要不为空就抓取全文返回，否则只返回摘要


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: true
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `news.qq.com/omn/author/:uid`
- `target`: `/qq/news/:uid`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/qq/news/8QMZ2X5a5YUeujw=",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": true,
    "supportScihub": false
  },
  "heat": 1,
  "location": "news/user.ts",
  "maintainers": [
    "hualiong"
  ],
  "name": "用户主页列表",
  "parameters": {
    "detail": "是否抓取全文，该值只要不为空就抓取全文返回，否则只返回摘要",
    "uid": "用户 ID, 用户主页 URL 中的最后一段部分"
  },
  "path": "/news/:uid/:detail?",
  "radar": [
    {
      "source": [
        "news.qq.com/omn/author/:uid"
      ],
      "target": "/qq/news/:uid"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
