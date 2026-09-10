# Google - Developers Blog

## Coverage
`index-only`

## Route
- Namespace: `google`
- Namespace Name: `Google`
- Route Path: `/google/developers/:locale?`
- Route Name: `Developers Blog`
- Example: `/google/developers/en`
- URL: `developers.googleblog.com`
- Language: `_None_`
- Categories: `blog`
- Maintainers: `Loongphy`
- Source Location: `developers.ts`
- Source Module: `_None_`

## Description
Google Developers Blog

## Parameters
- `locale`: {"default": "en", "description": "language", "options": [{"label": "English", "value": "en"}, {"label": "Español (Latam)", "value": "es"}, {"label": "Bahasa Indonesia", "value": "id"}, {"label": "日本語", "value": "ja"}, {"label": "한국어", "value": "ko"}, {"label": "Português (Brasil)", "value": "pt-br"}, {"label": "简体中文", "value": "zh-hans"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `developers.googleblog.com`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "description": "Google Developers Blog",
  "example": "/google/developers/en",
  "heat": 217,
  "location": "developers.ts",
  "maintainers": [
    "Loongphy"
  ],
  "name": "Developers Blog",
  "parameters": {
    "locale": {
      "default": "en",
      "description": "language",
      "options": [
        {
          "label": "English",
          "value": "en"
        },
        {
          "label": "Español (Latam)",
          "value": "es"
        },
        {
          "label": "Bahasa Indonesia",
          "value": "id"
        },
        {
          "label": "日本語",
          "value": "ja"
        },
        {
          "label": "한국어",
          "value": "ko"
        },
        {
          "label": "Português (Brasil)",
          "value": "pt-br"
        },
        {
          "label": "简体中文",
          "value": "zh-hans"
        }
      ]
    }
  },
  "path": "/developers/:locale?",
  "radar": [
    {
      "source": [
        "developers.googleblog.com"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Google Developers Blog - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "78683833365567488",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://developers.googleblog.com/",
      "title": "Google Developers Blog",
      "type": "feed",
      "url": "rsshub://google/developers/en"
    },
    {
      "description": "Google Developers Blog - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "78629527389615104",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://developers.googleblog.com/",
      "title": "Google Developers Blog",
      "type": "feed",
      "url": "rsshub://google/developers/zh-hans"
    }
  ],
  "url": "developers.googleblog.com"
}
```
