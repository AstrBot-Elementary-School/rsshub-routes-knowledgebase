# Ryo Lu - Journal

## Coverage
`index-only`

## Route
- Namespace: `ryo.lu`
- Namespace Name: `Ryo Lu`
- Route Path: `/ryo.lu/journal/:lang?`
- Route Name: `Journal`
- Example: `/ryo.lu/journal`
- URL: `ryo.lu/journal`
- Language: `_None_`
- Categories: `blog`
- Maintainers: `TonyRL`
- Source Location: `journal.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `lang`: {"default": "en", "description": "Language", "options": [{"label": "English", "value": "en"}, {"label": "中文", "value": "zh"}, {"label": "日本語", "value": "ja"}]}


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
  - `ryo.lu/journal`
  - `ryo.lu/`
- `target`: `/journal`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "example": "/ryo.lu/journal",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "journal.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Journal",
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
          "label": "中文",
          "value": "zh"
        },
        {
          "label": "日本語",
          "value": "ja"
        }
      ]
    }
  },
  "path": "/journal/:lang?",
  "radar": [
    {
      "source": [
        "ryo.lu/journal",
        "ryo.lu/"
      ],
      "target": "/journal"
    }
  ],
  "topFeeds": [],
  "url": "ryo.lu/journal",
  "view": 0
}
```
