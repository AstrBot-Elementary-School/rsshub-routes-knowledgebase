# 少数派 sspai - 作者

## Coverage
`index-only`

## Route
- Namespace: `sspai`
- Namespace Name: `少数派 sspai`
- Route Path: `/sspai/author/:id`
- Route Name: `作者`
- Example: `/sspai/author/796518`
- URL: `sspai.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `SunShinenny, hoilc`
- Source Location: `author.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 作者 slug 或 id，slug 可在作者主页URL中找到，id 不易查找，仅作兼容


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
  - `sspai.com/u/:id/posts`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/sspai/author/796518",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 166,
  "location": "author.ts",
  "maintainers": [
    "SunShinenny",
    "hoilc"
  ],
  "name": "作者",
  "parameters": {
    "id": "作者 slug 或 id，slug 可在作者主页URL中找到，id 不易查找，仅作兼容"
  },
  "path": "/author/:id",
  "radar": [
    {
      "source": [
        "sspai.com/u/:id/posts"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "玉树芝兰 更新推送 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "67269330696255569",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://sspai.com/u/a5xddvxl/posts",
      "title": "玉树芝兰 - 少数派作者",
      "type": "feed",
      "url": "rsshub://sspai/author/a5xddvxl"
    },
    {
      "description": "少数派编辑部 更新推送 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72521496466017287",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://sspai.com/u/ee0vj778/posts",
      "title": "少数派编辑部 - 少数派作者",
      "type": "feed",
      "url": "rsshub://sspai/author/ee0vj778"
    }
  ]
}
```
