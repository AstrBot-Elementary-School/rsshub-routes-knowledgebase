# BOOK☆WALKER - 搜尋

## Coverage
`index-only`

## Route
- Namespace: `bookwalker`
- Namespace Name: `BOOK☆WALKER`
- Route Path: `/bookwalker/search/:filter?`
- Route Name: `搜尋`
- Example: `/bookwalker/search/order=sell_desc&s=34`
- URL: `www.bookwalker.com.tw`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `wushijishan, nczitzk`
- Source Location: `search.tsx`
- Source Module: `_None_`

## Description
::: tip
订阅 [依發售日新至舊排序的文學小說](https://www.bookwalker.com.tw/search?order=sell_desc\&s=34)，其源网址为 `https://www.bookwalker.com.tw/search?order=sell_desc&s=34`，请参考该 URL 指定部分构成参数，此时路由为 [`/bookwalker/search/order=sell_desc&s=34`](https://rsshub.app/bookwalker/search/order=sell_desc\&s=34)。
:::

## Parameters
- `filter`: {"description": "过滤器，默认为 `order=sell_desc`，即依發售日新至舊排序"}


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
  - `www.bookwalker.com.tw/search`
- `target`: `/bookwalker/search`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "description": "::: tip\n订阅 [依發售日新至舊排序的文學小說](https://www.bookwalker.com.tw/search?order=sell_desc\\&s=34)，其源网址为 `https://www.bookwalker.com.tw/search?order=sell_desc&s=34`，请参考该 URL 指定部分构成参数，此时路由为 [`/bookwalker/search/order=sell_desc&s=34`](https://rsshub.app/bookwalker/search/order=sell_desc\\&s=34)。\n:::",
  "example": "/bookwalker/search/order=sell_desc&s=34",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 1,
  "location": "search.tsx",
  "maintainers": [
    "wushijishan",
    "nczitzk"
  ],
  "name": "搜尋",
  "parameters": {
    "filter": {
      "description": "过滤器，默认为 `order=sell_desc`，即依發售日新至舊排序"
    }
  },
  "path": "/search/:filter?",
  "radar": [
    {
      "source": [
        "www.bookwalker.com.tw/search"
      ],
      "target": "/bookwalker/search"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "搜尋： 系列 簡單顯示 依發售日新至舊排序 第1頁 BOOK☆WALKER 台灣漫讀 / 電子書平台 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "183720743964868608",
      "image": "https://www.bookwalker.com.tw/images/bookwalker.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.bookwalker.com.tw/search?order=sell_desc",
      "title": "搜尋： 系列 簡單顯示 依發售日新至舊排序 第1頁 BOOK☆WALKER 台灣漫讀 / 電子書平台",
      "type": "feed",
      "url": "rsshub://bookwalker/search"
    }
  ],
  "url": "www.bookwalker.com.tw",
  "view": 0
}
```
