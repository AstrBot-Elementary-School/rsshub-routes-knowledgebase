# Mercari - Search

## Coverage
`index-only`

## Route
- Namespace: `mercari`
- Namespace Name: `Mercari`
- Route Path: `/mercari/search/:query`
- Route Name: `Search`
- Example: `/mercari/search/keyword=シャツ&7bd3eacc-ae45-4d73-bc57-a611c9432014=340258ac-e220-4722-8c35-7f73b7382831`
- URL: `jp.mercari.com`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `yana9i, Tsuyumi25`
- Source Location: `search.ts`
- Source Module: `_None_`

## Description
::: warning
此路由僅支援 `jp.mercari.com`，不支援 `tw.mercari.com` 和 `hk.mercari.com`。

**注意：** 不同站點的查詢參數格式不同

- 日本: `keyword=シャツ&order=desc&sort=created_time&status=on_sale`
- 台灣: `keyword=シャツ&sort=new&status=in-stock&availability=1`

:::

## Parameters
- `query`: Search parameters in URL query string format.


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
    "shopping"
  ],
  "description": "::: warning\n此路由僅支援 `jp.mercari.com`，不支援 `tw.mercari.com` 和 `hk.mercari.com`。\n\n**注意：** 不同站點的查詢參數格式不同\n\n- 日本: `keyword=シャツ&order=desc&sort=created_time&status=on_sale`\n- 台灣: `keyword=シャツ&sort=new&status=in-stock&availability=1`\n\n:::",
  "example": "/mercari/search/keyword=シャツ&7bd3eacc-ae45-4d73-bc57-a611c9432014=340258ac-e220-4722-8c35-7f73b7382831",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "search.ts",
  "maintainers": [
    "yana9i",
    "Tsuyumi25"
  ],
  "name": "Search",
  "parameters": {
    "query": "Search parameters in URL query string format."
  },
  "path": "/search/:query",
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "jp.mercari.com"
}
```
