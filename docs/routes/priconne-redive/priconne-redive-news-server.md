# PRINCESS CONNECT! Re Dive プリンセスコネクト！Re Dive - 最新公告

## Coverage
`index-only`

## Route
- Namespace: `priconne-redive`
- Namespace Name: `PRINCESS CONNECT! Re Dive プリンセスコネクト！Re Dive`
- Route Path: `/priconne-redive/news/:server?`
- Route Name: `最新公告`
- Example: `/priconne-redive/news`
- URL: `priconne-redive.jp/news`
- Language: `_None_`
- Categories: `game`
- Maintainers: `SayaSS, frankcwl`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
服务器

| 国服  | 台服  | 日服 |
| ----- | ----- | ---- |
| zh-cn | zh-tw | jp   |

## Parameters
- `server`: 服务器，默认日服


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
  - `priconne-redive.jp/news`
- `target`: `/news/jp`
### Rule 2
- `source`:
  - `princessconnect.so-net.tw/news`
- `target`: `/news/zh-tw`
### Rule 3
- `source`:
  - `game.bilibili.com/pcr/news.html`
- `target`: `/news/zh-cn`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "服务器\n\n| 国服  | 台服  | 日服 |\n| ----- | ----- | ---- |\n| zh-cn | zh-tw | jp   |",
  "example": "/priconne-redive/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "news.ts",
  "maintainers": [
    "SayaSS",
    "frankcwl"
  ],
  "name": "最新公告",
  "parameters": {
    "server": "服务器，默认日服"
  },
  "path": "/news/:server?",
  "radar": [
    {
      "source": [
        "priconne-redive.jp/news"
      ],
      "target": "/news/jp"
    },
    {
      "source": [
        "princessconnect.so-net.tw/news"
      ],
      "target": "/news/zh-tw"
    },
    {
      "source": [
        "game.bilibili.com/pcr/news.html"
      ],
      "target": "/news/zh-cn"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "公主链接日服-新闻 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "127304052495781888",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://priconne-redive.jp/news/",
      "title": "公主链接日服-新闻",
      "type": "feed",
      "url": "rsshub://priconne-redive/news"
    },
    {
      "description": "公主连结台服-最新公告 - Powered by RSSHub",
      "errorAt": "2025-11-19T09:38:12.766Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "66023614482950154",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.princessconnect.so-net.tw/news",
      "title": "公主连结台服-最新公告",
      "type": "feed",
      "url": "rsshub://priconne-redive/news/zh-tw"
    }
  ],
  "url": "priconne-redive.jp/news"
}
```
