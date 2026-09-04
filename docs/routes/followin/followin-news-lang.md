# Followin - News

## Coverage
`index-only`

## Route
- Namespace: `followin`
- Namespace Name: `Followin`
- Route Path: `/followin/news/:lang?`
- Route Name: `News`
- Example: `/followin/news`
- URL: `followin.io`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `TonyRL`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `lang`: {"default": "en", "description": "Language", "options": [{"label": "English", "value": "en"}, {"label": "简体中文", "value": "zh-Hans"}, {"label": "繁體中文", "value": "zh-Hant"}, {"label": "Tiếng Việt", "value": "vi"}]}


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
  - `followin.io/:lang?/news`
  - `followin.io/news`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/followin/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 830,
  "location": "news.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "News",
  "parameters": {
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
  "path": "/news/:lang?",
  "radar": [
    {
      "source": [
        "followin.io/:lang?/news",
        "followin.io/news"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "News - Followin - Powered by RSSHub",
      "errorAt": "2026-08-20T01:29:45.299Z",
      "errorMessage": "Failed to fetch\n530 \n[GET] \"https://followin.io\": 429 Too Many Requests\n",
      "id": "64124473013636098",
      "image": "https://followin.io/favicon.ico",
      "ownerUserId": null,
      "siteUrl": "https://followin.io/en/news",
      "title": "News - Followin",
      "type": "feed",
      "url": "rsshub://followin/news"
    },
    {
      "description": "快讯 - Followin - Powered by RSSHub",
      "errorAt": "2026-08-19T09:54:04.768Z",
      "errorMessage": "[GET] \"https://followin.io\": 429 Too Many Requests\n",
      "id": "41419133062574080",
      "image": "https://followin.io/favicon.ico",
      "ownerUserId": null,
      "siteUrl": "https://followin.io/zh-Hans/news",
      "title": "快讯 - Followin",
      "type": "feed",
      "url": "rsshub://followin/news/zh-Hans"
    }
  ],
  "view": 0
}
```
