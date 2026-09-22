# Followin - Home

## Coverage
`index-only`

## Route
- Namespace: `followin`
- Namespace Name: `Followin`
- Route Path: `/followin/:categoryId?/:lang?`
- Route Name: `Home`
- Example: `/followin`
- URL: `followin.io`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `TonyRL`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
Category ID

| For You | Market | Meme | BRC20 | NFT | Thread | In-depth | Tutorials | Videos |
| ------- | ------ | ---- | ----- | --- | ------ | -------- | --------- | ------ |
| 1       | 9      | 13   | 14    | 3   | 5      | 6        | 8         | 11     |

Language

| English | 简体中文 | 繁體中文 | Tiếng Việt |
| ------- | -------- | -------- | ---------- |
| en      | zh-Hans  | zh-Hant  | vi         |

## Parameters
- `categoryId`: {"default": "1", "description": "Category ID", "options": [{"label": "For You", "value": "1"}, {"label": "Market", "value": "9"}, {"label": "Meme", "value": "13"}, {"label": "BRC20", "value": "14"}, {"label": "NFT", "value": "3"}, {"label": "Thread", "value": "5"}, {"label": "In-depth", "value": "6"}, {"label": "Tutorials", "value": "8"}, {"label": "Videos", "value": "11"}]}
- `lang`: {"default": "en", "description": "Language", "options": [{"label": "English", "value": "en"}, {"label": "简体中文", "value": "zh-Hans"}, {"label": "繁體中文", "value": "zh-Hant"}, {"label": "Tiếng Việt", "value": "vi"}]}


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
    "finance"
  ],
  "description": "Category ID\n\n| For You | Market | Meme | BRC20 | NFT | Thread | In-depth | Tutorials | Videos |\n| ------- | ------ | ---- | ----- | --- | ------ | -------- | --------- | ------ |\n| 1       | 9      | 13   | 14    | 3   | 5      | 6        | 8         | 11     |\n\nLanguage\n\n| English | 简体中文 | 繁體中文 | Tiếng Việt |\n| ------- | -------- | -------- | ---------- |\n| en      | zh-Hans  | zh-Hant  | vi         |",
  "example": "/followin",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 167,
  "location": "index.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Home",
  "parameters": {
    "categoryId": {
      "default": "1",
      "description": "Category ID",
      "options": [
        {
          "label": "For You",
          "value": "1"
        },
        {
          "label": "Market",
          "value": "9"
        },
        {
          "label": "Meme",
          "value": "13"
        },
        {
          "label": "BRC20",
          "value": "14"
        },
        {
          "label": "NFT",
          "value": "3"
        },
        {
          "label": "Thread",
          "value": "5"
        },
        {
          "label": "In-depth",
          "value": "6"
        },
        {
          "label": "Tutorials",
          "value": "8"
        },
        {
          "label": "Videos",
          "value": "11"
        }
      ]
    },
    "lang": {
      "default": "en",
      "description": "Language",
      "options": [
        {
          "label": "English",
          "value": "en"
        },
        {
          "label": "简体中文",
          "value": "zh-Hans"
        },
        {
          "label": "繁體中文",
          "value": "zh-Hant"
        },
        {
          "label": "Tiếng Việt",
          "value": "vi"
        }
      ]
    }
  },
  "path": "/:categoryId?/:lang?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Followin - Powered by RSSHub",
      "errorAt": "2026-08-21T19:43:29.493Z",
      "errorMessage": "[GET] \"https://followin.io\": 429 Too Many Requests\n",
      "id": "72596134870584320",
      "image": "https://followin.io/favicon.ico",
      "ownerUserId": null,
      "siteUrl": "https://followin.io/",
      "title": "Followin",
      "type": "feed",
      "url": "rsshub://followin/1"
    },
    {
      "description": "Followin - Powered by RSSHub",
      "errorAt": "2026-08-20T07:10:32.583Z",
      "errorMessage": "Failed to fetch\n",
      "id": "62849148807841792",
      "image": "https://followin.io/favicon.ico",
      "ownerUserId": null,
      "siteUrl": "https://followin.io/",
      "title": "Followin",
      "type": "feed",
      "url": "rsshub://followin/1/zh-Hans"
    }
  ],
  "view": 0
}
```
