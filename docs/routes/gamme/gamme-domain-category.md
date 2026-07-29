# 卡卡洛普 - 分類

## Coverage
`index-only`

## Route
- Namespace: `gamme`
- Namespace Name: `卡卡洛普`
- Route Path: `/gamme/:domain/:category?`
- Route Name: `分類`
- Example: `/gamme/news`
- URL: `news.gamme.com.tw`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `category.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `domain`: 網站，`news` 為宅宅新聞，`sexynews` 為西斯新聞
- `category`: 分類名，可在 URL 找到，預設為全部


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/gamme/news",
  "heat": 27,
  "location": "category.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "分類",
  "parameters": {
    "category": "分類名，可在 URL 找到，預設為全部",
    "domain": "網站，`news` 為宅宅新聞，`sexynews` 為西斯新聞"
  },
  "path": "/:domain/:category?",
  "topFeeds": [
    {
      "description": "新奇／潮流／正妹／奇事 通通在這裡～ - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "73007806617184256",
      "image": "https://news.gamme.com.tw/blogico.ico",
      "ownerUserId": null,
      "siteUrl": "https://news.gamme.com.tw/category/all",
      "title": "宅宅新聞 by 卡卡洛普 » 最新",
      "type": "feed",
      "url": "rsshub://gamme/news/all"
    },
    {
      "description": "新奇／潮流／正妹／奇事 通通在這裡～ - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "87402345385114631",
      "image": "https://news.gamme.com.tw/blogico.ico",
      "ownerUserId": null,
      "siteUrl": "https://news.gamme.com.tw/category/all",
      "title": "宅宅新聞 by 卡卡洛普 » 最新",
      "type": "feed",
      "url": "rsshub://gamme/news"
    }
  ]
}
```
