# 鏡週刊 Mirror Media - 分类

## Coverage
`index-only`

## Route
- Namespace: `mirrormedia`
- Namespace Name: `鏡週刊 Mirror Media`
- Route Path: `/mirrormedia/category/:category`
- Route Name: `分类`
- Example: `/mirrormedia/category/political`
- URL: `mirrormedia.mg`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `dzx-dzx`
- Source Location: `category.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: 分类名
- `section`: 子板名


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `mirrormedia.mg/category/:category`
  - `mirrormedia.mg/section/:section`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/mirrormedia/category/political",
  "heat": 35,
  "location": "category.ts",
  "maintainers": [
    "dzx-dzx"
  ],
  "name": "分类",
  "parameters": {
    "category": "分类名",
    "section": "子板名"
  },
  "path": [
    "/category/:category",
    "/section/:section"
  ],
  "radar": [
    {
      "source": [
        "mirrormedia.mg/category/:category",
        "mirrormedia.mg/section/:section"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "鏡週刊 Mirror Media - political - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "57027261715751936",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.mirrormedia.mg/",
      "title": "鏡週刊 Mirror Media - political",
      "type": "feed",
      "url": "rsshub://mirrormedia/category/political"
    },
    {
      "description": "鏡週刊 Mirror Media - city-news - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "131968010464549888",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.mirrormedia.mg/",
      "title": "鏡週刊 Mirror Media - city-news",
      "type": "feed",
      "url": "rsshub://mirrormedia/category/city-news"
    }
  ]
}
```
