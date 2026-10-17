# Odaily 星球日报 - 文章

## Coverage
`index-only`

## Route
- Namespace: `odaily`
- Namespace Name: `Odaily 星球日报`
- Route Path: `/odaily/:id{280}?`
- Route Name: `文章`
- Example: `/odaily`
- URL: `www.odaily.news/zh-CN/post`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `post.ts`
- Source Module: `_None_`

## Description
最新文章。旧版分类接口已下线，目前仅保留最新文章订阅。

## Parameters
- `id`: 仅支持最新文章（280），省略时同样返回最新文章。旧分类接口已下线。


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
  - `www.odaily.news/`
  - `www.odaily.news/:locale/post`
- `target`: `/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "最新文章。旧版分类接口已下线，目前仅保留最新文章订阅。",
  "example": "/odaily",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 107,
  "location": "post.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "文章",
  "parameters": {
    "id": "仅支持最新文章（280），省略时同样返回最新文章。旧分类接口已下线。"
  },
  "path": "/:id{280}?",
  "radar": [
    {
      "source": [
        "www.odaily.news/",
        "www.odaily.news/:locale/post"
      ],
      "target": "/"
    }
  ],
  "topFeeds": [
    {
      "description": "最新 - Odaily星球日报 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "56204588915011597",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.odaily.news/",
      "title": "最新 - Odaily星球日报",
      "type": "feed",
      "url": "rsshub://odaily"
    },
    {
      "description": "最新 - Odaily星球日报 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "85203770103696384",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.odaily.news/",
      "title": "最新 - Odaily星球日报",
      "type": "feed",
      "url": "rsshub://odaily/280"
    }
  ],
  "url": "www.odaily.news/zh-CN/post"
}
```
