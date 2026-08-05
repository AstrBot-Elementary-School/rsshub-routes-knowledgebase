# 蓝点网 - 分类

## Coverage
`index-only`

## Route
- Namespace: `landiannews`
- Namespace Name: `蓝点网`
- Route Path: `/landiannews/category/:slug`
- Route Name: `分类`
- Example: `/landiannews/category/sells`
- URL: `www.landiannews.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `cscnk52`
- Source Location: `category.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `slug`: 分类名称


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
  - `www.landiannews.com/:slug`
- `target`: `/category/:slug`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/landiannews/category/sells",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 6,
  "location": "category.ts",
  "maintainers": [
    "cscnk52"
  ],
  "name": "分类",
  "parameters": {
    "slug": "分类名称"
  },
  "path": "/category/:slug",
  "radar": [
    {
      "source": [
        "www.landiannews.com/:slug"
      ],
      "target": "/category/:slug"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "给你感兴趣的内容! - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "114833612717202432",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.landiannews.com/ai",
      "title": "人工智能 - 蓝点网",
      "type": "feed",
      "url": "rsshub://landiannews/category/ai"
    }
  ],
  "url": "www.landiannews.com",
  "view": 0
}
```
