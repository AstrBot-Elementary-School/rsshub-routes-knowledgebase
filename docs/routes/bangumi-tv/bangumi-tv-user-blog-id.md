# Bangumi 番组计划 - 用户日志

## Coverage
`index-only`

## Route
- Namespace: `bangumi.tv`
- Namespace Name: `Bangumi 番组计划`
- Route Path: `/bangumi.tv/user/blog/:id`
- Route Name: `用户日志`
- Example: `/bangumi.tv/user/blog/sai`
- URL: `bangumi.tv`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `nczitzk`
- Source Location: `user/blog.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 用户 id, 在用户页面地址栏查看


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
  - `bgm.tv/user/:id`
### Rule 2
- `source`:
  - `bangumi.tv/user/:id`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/bangumi.tv/user/blog/sai",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 10,
  "location": "user/blog.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "用户日志",
  "parameters": {
    "id": "用户 id, 在用户页面地址栏查看"
  },
  "path": "/user/blog/:id",
  "radar": [
    {
      "source": [
        "bgm.tv/user/:id"
      ]
    },
    {
      "source": [
        "bangumi.tv/user/:id"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "shiraki的日志 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "133404410744743936",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bgm.tv/user/shiraki/blog",
      "title": "shiraki的日志",
      "type": "feed",
      "url": "rsshub://bangumi.tv/user/blog/shiraki"
    },
    {
      "description": "苍旻白轮的日志 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "150221176980773888",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bgm.tv/user/whitering/blog",
      "title": "苍旻白轮的日志",
      "type": "feed",
      "url": "rsshub://bangumi.tv/user/blog/whitering"
    }
  ]
}
```
