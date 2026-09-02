# Netflix - Newsroom

## Coverage
`index-only`

## Route
- Namespace: `netflix`
- Namespace Name: `Netflix`
- Route Path: `/netflix/newsroom/:category?/:region?`
- Route Name: `Newsroom`
- Example: `/netflix/newsroom`
- URL: `about.netflix.com/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `newsroom.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: {"default": "all", "description": "Category", "options": [{"label": "All News", "value": "all"}, {"label": "Business", "value": "business"}, {"label": "Entertainment", "value": "entertainment"}, {"label": "Product", "value": "product"}, {"label": "Social Impact", "value": "impact"}]}
- `region`: {"default": "en", "description": "Region, can be found in the region URL", "options": [{"label": "اللغة العربية", "value": "ar"}, {"label": "Deutsch", "value": "de"}, {"label": "Ελληνικά", "value": "el"}, {"label": "English", "value": "en"}, {"label": "Español (LatAm)", "value": "es"}, {"label": "Español (España)", "value": "es-es"}, {"label": "Français", "value": "fr"}, {"label": "Bahasa Indonesia", "value": "id"}, {"label": "Italiano", "value": "it"}, {"label": "日本語", "value": "ja"}, {"label": "한국어", "value": "ko"}, {"label": "Polski", "value": "pl"}, {"label": "Português (Brasil)", "value": "pt-br"}, {"label": "Português (Portugal)", "value": "pt-pt"}, {"label": "Română", "value": "ro"}, {"label": "русский", "value": "ru"}, {"label": "ไทย", "value": "th"}, {"label": "Türkçe", "value": "tr"}, {"label": "Tiếng Việt", "value": "vi"}, {"label": "简体中文", "value": "zh-hans"}, {"label": "繁體中文", "value": "zh-hant"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `about.netflix.com/:region/newsroom`
### Rule 2
- `source`:
  - `netflix.com`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/netflix/newsroom",
  "heat": 7,
  "location": "newsroom.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Newsroom",
  "parameters": {
    "category": {
      "default": "all",
      "description": "Category",
      "options": [
        {
          "label": "All News",
          "value": "all"
        },
        {
          "label": "Business",
          "value": "business"
        },
        {
          "label": "Entertainment",
          "value": "entertainment"
        },
        {
          "label": "Product",
          "value": "product"
        },
        {
          "label": "Social Impact",
          "value": "impact"
        }
      ]
    },
    "region": {
      "default": "en",
      "description": "Region, can be found in the region URL",
      "options": [
        {
          "label": "اللغة العربية",
          "value": "ar"
        },
        {
          "label": "Deutsch",
          "value": "de"
        },
        {
          "label": "Ελληνικά",
          "value": "el"
        },
        {
          "label": "English",
          "value": "en"
        },
        {
          "label": "Español (LatAm)",
          "value": "es"
        },
        {
          "label": "Español (España)",
          "value": "es-es"
        },
        {
          "label": "Français",
          "value": "fr"
        },
        {
          "label": "Bahasa Indonesia",
          "value": "id"
        },
        {
          "label": "Italiano",
          "value": "it"
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
          "label": "Polski",
          "value": "pl"
        },
        {
          "label": "Português (Brasil)",
          "value": "pt-br"
        },
        {
          "label": "Português (Portugal)",
          "value": "pt-pt"
        },
        {
          "label": "Română",
          "value": "ro"
        },
        {
          "label": "русский",
          "value": "ru"
        },
        {
          "label": "ไทย",
          "value": "th"
        },
        {
          "label": "Türkçe",
          "value": "tr"
        },
        {
          "label": "Tiếng Việt",
          "value": "vi"
        },
        {
          "label": "简体中文",
          "value": "zh-hans"
        },
        {
          "label": "繁體中文",
          "value": "zh-hant"
        }
      ]
    }
  },
  "path": "/newsroom/:category?/:region?",
  "radar": [
    {
      "source": [
        "about.netflix.com/:region/newsroom"
      ]
    },
    {
      "source": [
        "netflix.com"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "All News - Newsroom - Netflix - Powered by RSSHub",
      "errorAt": "2026-08-31T20:22:42.793Z",
      "errorMessage": "Unhandled node type: blockquote\n",
      "id": "191666157347082245",
      "image": "https://about.netflix.com/favicon.ico",
      "ownerUserId": null,
      "siteUrl": "https://about.netflix.com/en/newsroom",
      "title": "All News - Newsroom - Netflix",
      "type": "feed",
      "url": "rsshub://netflix/newsroom"
    },
    {
      "description": "All News - Newsroom - Netflix - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "244319118695723008",
      "image": "https://about.netflix.com/favicon.ico",
      "ownerUserId": null,
      "siteUrl": "https://about.netflix.com/zh-hans/newsroom",
      "title": "All News - Newsroom - Netflix",
      "type": "feed",
      "url": "rsshub://netflix/newsroom/all/zh-hans"
    }
  ],
  "url": "about.netflix.com/"
}
```
