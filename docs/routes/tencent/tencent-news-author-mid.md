# 腾讯 - 作者

## Coverage
`index-only`

## Route
- Namespace: `tencent`
- Namespace Name: `腾讯`
- Route Path: `/tencent/news/author/:mid`
- Route Name: `作者`
- Example: `/tencent/news/author/5933889`
- URL: `tencent.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `LogicJake, miles170`
- Source Location: `news/author.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `mid`: 企鹅号 ID


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `title`: `当前作者文章`
- `source`:
  - `news.qq.com/omn/author/:mid`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/tencent/news/author/5933889",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 761,
  "location": "news/author.tsx",
  "maintainers": [
    "LogicJake",
    "miles170"
  ],
  "name": "作者",
  "parameters": {
    "mid": "企鹅号 ID"
  },
  "path": "/news/author/:mid",
  "radar": [
    {
      "source": [
        "news.qq.com/omn/author/:mid"
      ],
      "title": "当前作者文章"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "腾讯新闻出品栏目，关注科技和TMT领域公司、事件和人物中的故事，探究背后的深层逻辑。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "61256473379615744",
      "image": "https://inews.gtimg.com/newsapp_ls/0/14314588661_200200/0",
      "ownerUserId": null,
      "siteUrl": "https://new.qq.com/omn/author/5157372",
      "title": "深网",
      "type": "feed",
      "url": "rsshub://tencent/news/author/5157372"
    },
    {
      "description": "腾讯新闻出品、谷雨工作室旗下栏目，聚焦深度图文内容。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "64116243042231296",
      "image": "http://inews.gtimg.com/newsapp_ls/0/14306093309_200200/0",
      "ownerUserId": null,
      "siteUrl": "https://new.qq.com/omn/author/5505476",
      "title": "谷雨实验室",
      "type": "feed",
      "url": "rsshub://tencent/news/author/5505476"
    }
  ]
}
```
