# 恩山无线论坛 - 板块

## Coverage
`index-only`

## Route
- Namespace: `right`
- Namespace Name: `恩山无线论坛`
- Route Path: `/right/forum/:id?`
- Route Name: `板块`
- Example: `/right/forum/31`
- URL: `right.com.cn`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `nczitzk`
- Source Location: `forum.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 板块 id，可在板块页 URL 中找到，默认为新手入门及其它(硬件)


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
    "bbs"
  ],
  "example": "/right/forum/31",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 528,
  "location": "forum.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "板块",
  "parameters": {
    "id": "板块 id，可在板块页 URL 中找到，默认为新手入门及其它(硬件)"
  },
  "path": "/forum/:id?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "国内iptv、软件、代码、源 - 恩山无线论坛 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "54806809341165571",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.right.com.cn/forum/forum-182-1.html",
      "title": "国内iptv、软件、代码、源 - 恩山无线论坛",
      "type": "feed",
      "url": "rsshub://right/forum/182"
    },
    {
      "description": "新手入门及其它(硬件) - 恩山无线论坛 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "61252164758378512",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.right.com.cn/forum/forum-31-1.html",
      "title": "新手入门及其它(硬件) - 恩山无线论坛",
      "type": "feed",
      "url": "rsshub://right/forum/31"
    }
  ]
}
```
