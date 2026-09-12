# Taiwan FactCheck Center - 分類

## Coverage
`index-only`

## Route
- Namespace: `tfc-taiwan`
- Namespace Name: `Taiwan FactCheck Center`
- Route Path: `/tfc-taiwan/category/:category`
- Route Name: `分類`
- Example: `/tfc-taiwan/category/weekly-top-ten-rumors`
- URL: `tfc-taiwan.org.tw/category/rumor-mill/`
- Language: `_None_`
- Categories: `other`
- Maintainers: `TonyRL`
- Source Location: `category.ts`
- Source Module: `_None_`

## Description
| 謠言風向球 | 議題觀察室        | TOP10                 | 名家專欄       | 國際視野             |
| ---------- | ----------------- | --------------------- | -------------- | -------------------- |
| rumor-mill | issue-observatory | weekly-top-ten-rumors | expert-columns | research-and-updates |

## Parameters
- `category`: 分類，見下表，預設為 `weekly-top-ten-rumors`


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "| 謠言風向球 | 議題觀察室        | TOP10                 | 名家專欄       | 國際視野             |\n| ---------- | ----------------- | --------------------- | -------------- | -------------------- |\n| rumor-mill | issue-observatory | weekly-top-ten-rumors | expert-columns | research-and-updates |",
  "example": "/tfc-taiwan/category/weekly-top-ten-rumors",
  "heat": 2,
  "location": "category.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "分類",
  "parameters": {
    "category": "分類，見下表，預設為 `weekly-top-ten-rumors`"
  },
  "path": "/category/:category",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "台灣事實查核中心 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "156051053062277123",
      "image": "https://tfc-taiwan.org.tw/wp-content/uploads/2024/12/yoast-seo-logo-setup.jpg",
      "ownerUserId": null,
      "siteUrl": "https://tfc-taiwan.org.tw/category/weekly-top-ten-rumors/",
      "title": "〈每週謠言TOP10 〉彙整頁面 - 台灣事實查核中心",
      "type": "feed",
      "url": "rsshub://tfc-taiwan/category/weekly-top-ten-rumors"
    },
    {
      "description": "謠言風向球 | 台灣事實查核中心 - Powered by RSSHub",
      "errorAt": "2025-01-10T16:35:10.484Z",
      "errorMessage": "[GET] \"https://tfc-taiwan.org.tw/wp-json/wp/v2/categories/242\": 404 Not Found\n",
      "id": "74104089253902336",
      "image": "https://tfc-taiwan.org.tw/sites/all/themes/tfc_ogimage.jpeg",
      "ownerUserId": null,
      "siteUrl": "https://tfc-taiwan.org.tw/articles/category/242",
      "title": "謠言風向球 | 台灣事實查核中心",
      "type": "feed",
      "url": "rsshub://tfc-taiwan/category/242"
    }
  ],
  "url": "tfc-taiwan.org.tw/category/rumor-mill/"
}
```
