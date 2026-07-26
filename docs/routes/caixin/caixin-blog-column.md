# 财新博客 - 用户博客

## Coverage
`index-only`

## Route
- Namespace: `caixin`
- Namespace Name: `财新博客`
- Route Path: `/caixin/blog/:column?`
- Route Name: `用户博客`
- Example: `/caixin/blog/zhangwuchang`
- URL: `caixin.com`
- Language: `_None_`
- Categories: `blog`
- Maintainers: `None`
- Source Location: `blog.ts`
- Source Module: `_None_`

## Description
通过提取文章全文，以提供比官方源更佳的阅读体验.

## Parameters
- `column`: 博客名称，可在博客主页的 URL 找到


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
    "blog"
  ],
  "description": "通过提取文章全文，以提供比官方源更佳的阅读体验.",
  "example": "/caixin/blog/zhangwuchang",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 359,
  "location": "blog.ts",
  "maintainers": [],
  "name": "用户博客",
  "parameters": {
    "column": "博客名称，可在博客主页的 URL 找到"
  },
  "path": "/blog/:column?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "财新博客 - 全部 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "55178154415140877",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://blog.caixin.com/",
      "title": "财新博客 - 全部",
      "type": "feed",
      "url": "rsshub://caixin/blog"
    },
    {
      "description": "香港经济学家，新制度经济学代表人物之一，毕业于美国加利福尼亚大学洛杉矶分校经济学系。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "57047965780416535",
      "image": "https://getavatar.caixin.com/000/00/25/44_real_avatar_middle.jpg",
      "ownerUserId": null,
      "siteUrl": "https://zhangwuchang.blog.caixin.com/",
      "title": "财新博客 - 张五常",
      "type": "feed",
      "url": "rsshub://caixin/blog/zhangwuchang"
    }
  ]
}
```
