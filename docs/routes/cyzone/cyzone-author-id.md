# 创业邦 - 作者

## Coverage
`index-only`

## Route
- Namespace: `cyzone`
- Namespace Name: `创业邦`
- Route Path: `/cyzone/author/:id`
- Route Name: `作者`
- Example: `/cyzone/author/1225562`
- URL: `cyzone.cn`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `xyqfer, nczitzk`
- Source Location: `author.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 作者 id，可在对应作者页 URL 中找到


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
  - `cyzone.cn/author/:id`
  - `cyzone.cn/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/cyzone/author/1225562",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 24,
  "location": "author.ts",
  "maintainers": [
    "xyqfer",
    "nczitzk"
  ],
  "name": "作者",
  "parameters": {
    "id": "作者 id，可在对应作者页 URL 中找到"
  },
  "path": "/author/:id",
  "radar": [
    {
      "source": [
        "cyzone.cn/author/:id",
        "cyzone.cn/"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "《商业评论》出品，用深度案例、前沿观点，和你一起探索新零售的1001种可能。 - Powered by RSSHub",
      "errorAt": "2026-06-12T07:58:21.522Z",
      "errorMessage": "Failed to fetch\n",
      "id": "110577462466842624",
      "image": "https://oss.cyzone.cn/2022/0209/9a5a6a31cf83b57e6f8b9dce4f98c367.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.cyzone.cn/author/1736838",
      "title": "新消费101 - 专栏作者 - 创业邦",
      "type": "feed",
      "url": "rsshub://cyzone/author/1736838"
    },
    {
      "description": "幼年茂盛，童年饱满，少年错愕，青年踏上新的拐点。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "120022882443320320",
      "image": "https://oss.cyzone.cn/2018/1130/db8dcd20127a05e2a08b6381b2ea2b15.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.cyzone.cn/author/1225562",
      "title": "夏弢 - 专栏作者 - 创业邦",
      "type": "feed",
      "url": "rsshub://cyzone/author/1225562"
    }
  ]
}
```
