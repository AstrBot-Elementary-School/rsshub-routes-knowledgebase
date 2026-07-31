# 4Gamers - 分类

## Coverage
`index-only`

## Route
- Namespace: `4gamers`
- Namespace Name: `4Gamers`
- Route Path: `/4gamers/category/:category`
- Route Name: `分类`
- Example: `/4gamers/category/352`
- URL: `www.4gamers.com.tw/news`
- Language: `_None_`
- Categories: `game`
- Maintainers: `TonyRL`
- Source Location: `category.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: 分类 ID，可从分类 URL 中找到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.4gamers.com.tw/news/category/:category/:categoryName`
- `target`: `/category/:category`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/4gamers/category/352",
  "heat": 184,
  "location": "category.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "分类",
  "parameters": {
    "category": "分类 ID，可从分类 URL 中找到"
  },
  "path": "/category/:category",
  "radar": [
    {
      "source": [
        "www.4gamers.com.tw/news/category/:category/:categoryName"
      ],
      "target": "/category/:category"
    }
  ],
  "topFeeds": [
    {
      "description": "4Gamers - 成人限定🔞 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72578894783772672",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.4gamers.com.tw/news/category/1119/%E6%88%90%E4%BA%BA%E9%99%90%E5%AE%9A%F0%9F%94%9E",
      "title": "4Gamers - 成人限定🔞",
      "type": "feed",
      "url": "rsshub://4gamers/category/1119"
    },
    {
      "description": "4Gamers - 深度專題 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "66771599303537672",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.4gamers.com.tw/news/category/359/%E6%B7%B1%E5%BA%A6%E5%B0%88%E9%A1%8C",
      "title": "4Gamers - 深度專題",
      "type": "feed",
      "url": "rsshub://4gamers/category/359"
    }
  ],
  "url": "www.4gamers.com.tw/news"
}
```
