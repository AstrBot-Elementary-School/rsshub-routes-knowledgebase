# Plurk - Top

## Coverage
`index-only`

## Route
- Namespace: `plurk`
- Namespace Name: `Plurk`
- Route Path: `/plurk/top/:category?/:lang?`
- Route Name: `Top`
- Example: `/plurk/top/topReplurks`
- URL: `plurk.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `TonyRL`
- Source Location: `top.ts`
- Source Module: `_None_`

## Description
| Top Replurks | Top Favorites | Top Responded |
| ------------ | ------------- | ------------- |
| topReplurks  | topFavorites  | topResponded  |

| English | 中文（繁體） |
| ------- | ------------ |
| en      | zh           |

## Parameters
- `category`: Category, see the table below, `topReplurks` by default
- `lang`: Language, see the table below, `en` by default


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
  "description": "| Top Replurks | Top Favorites | Top Responded |\n| ------------ | ------------- | ------------- |\n| topReplurks  | topFavorites  | topResponded  |\n\n| English | 中文（繁體） |\n| ------- | ------------ |\n| en      | zh           |",
  "example": "/plurk/top/topReplurks",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 53,
  "location": "top.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Top",
  "parameters": {
    "category": "Category, see the table below, `topReplurks` by default",
    "lang": "Language, see the table below, `en` by default"
  },
  "path": "/top/:category?/:lang?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Top Plurk - Plurk - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "71897893377004544",
      "image": "https://s.plurk.com/2c1574c02566f3b06e91.png",
      "ownerUserId": null,
      "siteUrl": "https://www.plurk.com/top#topReplurks",
      "title": "Top Plurk - Plurk",
      "type": "feed",
      "url": "rsshub://plurk/top"
    },
    {
      "description": "Top Plurk - Plurk - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "75060543263661056",
      "image": "https://s.plurk.com/2c1574c02566f3b06e91.png",
      "ownerUserId": null,
      "siteUrl": "https://www.plurk.com/top#topReplurks",
      "title": "Top Plurk - Plurk",
      "type": "feed",
      "url": "rsshub://plurk/top/topReplurks/zh"
    }
  ],
  "view": 1
}
```
