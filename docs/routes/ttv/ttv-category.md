# 台視新聞網 - 分类

## Coverage
`index-only`

## Route
- Namespace: `ttv`
- Namespace Name: `台視新聞網`
- Route Path: `/ttv/:category?`
- Route Name: `分类`
- Example: `/ttv`
- URL: `news.ttv.com.tw`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `dzx-dzx`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: 分类


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `news.ttv.com.tw/:category`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/ttv",
  "heat": 65,
  "location": "index.ts",
  "maintainers": [
    "dzx-dzx"
  ],
  "name": "分类",
  "parameters": {
    "category": "分类"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "news.ttv.com.tw/:category"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "台視新聞 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72920871518882818",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://news.ttv.com.tw/realtime",
      "title": "台視新聞",
      "type": "feed",
      "url": "rsshub://ttv"
    },
    {
      "description": "台視新聞網 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "131972776479638528",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://news.ttv.com.tw/category/%E6%94%BF%E6%B2%BB",
      "title": "台視新聞網",
      "type": "feed",
      "url": "rsshub://ttv/%E6%94%BF%E6%B2%BB"
    }
  ]
}
```
