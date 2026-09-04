# 哔哩哔哩 bilibili - 专栏文集

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/bilibili/readlist/:listid`
- Route Name: `专栏文集`
- Example: `/bilibili/readlist/25611`
- URL: `www.bilibili.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `hoilc`
- Source Location: `readlist.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `listid`: 文集 id, 可在专栏文集 URL 中找到


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
    "social-media"
  ],
  "example": "/bilibili/readlist/25611",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 87,
  "location": "readlist.ts",
  "maintainers": [
    "hoilc"
  ],
  "name": "专栏文集",
  "parameters": {
    "listid": "文集 id, 可在专栏文集 URL 中找到"
  },
  "path": "/readlist/:listid",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "bilibili 专栏文集 - Galgame - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "61348871765397504",
      "image": "http://i0.hdslb.com/bfs/article/d1b4ff3871674fb8c7cca0e7e7c13061c0067488.png",
      "ownerUserId": null,
      "siteUrl": "https://www.bilibili.com/read/readlist/rl25611",
      "title": "bilibili 专栏文集 - Galgame",
      "type": "feed",
      "url": "rsshub://bilibili/readlist/25611"
    },
    {
      "description": "新番导视 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72902324883282944",
      "image": "http://i0.hdslb.com/bfs/article/be670d9f8ce40aa64d272203eda3a26825027e64.png",
      "ownerUserId": null,
      "siteUrl": "https://www.bilibili.com/read/readlist/rl153371",
      "title": "bilibili 专栏文集 - 【新番导视】",
      "type": "feed",
      "url": "rsshub://bilibili/readlist/153371"
    }
  ],
  "view": 0
}
```
