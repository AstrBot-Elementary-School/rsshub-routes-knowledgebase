# 链新闻 ABMedia - 类别

## Coverage
`index-only`

## Route
- Namespace: `abmedia`
- Namespace Name: `链新闻 ABMedia`
- Route Path: `/abmedia/:category?`
- Route Name: `类别`
- Example: `/abmedia/technology-development`
- URL: `www.abmedia.io`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `Fatpandac`
- Source Location: `category.ts`
- Source Module: `_None_`

## Description
参数可以从链接中拿到，如：

`https://www.abmedia.io/category/technology-development` 对应 `/abmedia/technology-development`

## Parameters
- `category`: 类别，默认为产品技术


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
  - `www.abmedia.io/category/:catehory`
- `target`: `/:category`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "参数可以从链接中拿到，如：\n\n`https://www.abmedia.io/category/technology-development` 对应 `/abmedia/technology-development`",
  "example": "/abmedia/technology-development",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "category.ts",
  "maintainers": [
    "Fatpandac"
  ],
  "name": "类别",
  "parameters": {
    "category": "类别，默认为产品技术"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "www.abmedia.io/category/:catehory"
      ],
      "target": "/:category"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
