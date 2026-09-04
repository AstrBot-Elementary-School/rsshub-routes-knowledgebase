# 禁漫天堂 - 搜索

## Coverage
`index-only`

## Route
- Namespace: `18comic`
- Namespace Name: `禁漫天堂`
- Route Path: `/18comic/search/:option?/:category?/:keyword?/:time?/:order?`
- Route Name: `搜索`
- Example: `/18comic/search/photos/all/NTR`
- URL: `jmcomic.group/`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `nczitzk, pseudoyu`
- Source Location: `search.ts`
- Source Module: `_None_`

## Description
::: tip
关键字必须超过两个字，这是来自网站的限制。
:::

## Parameters
- `option`: 选项，可选 `video` 和 `photos`，默认为 `photos`
- `category`: 分类，同上表，默认为 `all` 即全部
- `keyword`: 关键字，同上表，默认为空
- `time`: 时间范围，同上表，默认为 `a` 即全部
- `order`: 排列顺序，同上表，默认为 `mr` 即最新


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `jmcomic.group/`
- `target`: `/:category?/:time?/:order?/:keyword?`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "description": "::: tip\n关键字必须超过两个字，这是来自网站的限制。\n:::",
  "example": "/18comic/search/photos/all/NTR",
  "features": {
    "antiCrawler": true,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 99,
  "location": "search.ts",
  "maintainers": [
    "nczitzk",
    "pseudoyu"
  ],
  "name": "搜索",
  "parameters": {
    "category": "分类，同上表，默认为 `all` 即全部",
    "keyword": "关键字，同上表，默认为空",
    "option": "选项，可选 `video` 和 `photos`，默认为 `photos`",
    "order": "排列顺序，同上表，默认为 `mr` 即最新",
    "time": "时间范围，同上表，默认为 `a` 即全部"
  },
  "path": "/search/:option?/:category?/:keyword?/:time?/:order?",
  "radar": [
    {
      "source": [
        "jmcomic.group/"
      ],
      "target": "/:category?/:time?/:order?/:keyword?"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Search Results For '' - 禁漫天堂 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "163668204999134208",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://jmcomic1.me/search/photos",
      "title": "Search Results For '' - 禁漫天堂",
      "type": "feed",
      "url": "rsshub://18comic/search"
    },
    {
      "description": "Search Results For '' - 禁漫天堂 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "175372537489518592",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://jmcomic1.me/search/photos",
      "title": "Search Results For '' - 禁漫天堂",
      "type": "feed",
      "url": "rsshub://18comic/search/photos"
    }
  ],
  "url": "jmcomic.group/"
}
```
