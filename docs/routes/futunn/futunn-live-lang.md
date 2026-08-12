# Futubull 富途牛牛 - 快讯

## Coverage
`index-only`

## Route
- Namespace: `futunn`
- Namespace Name: `Futubull 富途牛牛`
- Route Path: `/futunn/live/:lang?`
- Route Name: `快讯`
- Example: `/futunn/live`
- URL: `news.futunn.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `kennyfong19931`
- Source Location: `live.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: {"default": "Mandarin", "description": "通知语言", "options": [{"label": "国语", "value": "Mandarin"}, {"label": "粵語", "value": "Cantonese"}, {"label": "English", "value": "English"}]}


## Features
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `news.futunn.com/main/live`
- `target`: `/live`
### Rule 2
- `source`:
  - `news.futunn.com/hk/main/live`
- `target`: `/live/Cantonese`
### Rule 3
- `source`:
  - `news.futunn.com/en/main/live`
- `target`: `/live/English`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/futunn/live",
  "features": {
    "supportRadar": true
  },
  "heat": 20,
  "location": "live.ts",
  "maintainers": [
    "kennyfong19931"
  ],
  "name": "快讯",
  "parameters": {
    "category": {
      "default": "Mandarin",
      "description": "通知语言",
      "options": [
        {
          "label": "国语",
          "value": "Mandarin"
        },
        {
          "label": "粵語",
          "value": "Cantonese"
        },
        {
          "label": "English",
          "value": "English"
        }
      ]
    }
  },
  "path": "/live/:lang?",
  "radar": [
    {
      "source": [
        "news.futunn.com/main/live"
      ],
      "target": "/live"
    },
    {
      "source": [
        "news.futunn.com/hk/main/live"
      ],
      "target": "/live/Cantonese"
    },
    {
      "source": [
        "news.futunn.com/en/main/live"
      ],
      "target": "/live/English"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "富途牛牛 - 快讯 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "212343743490256896",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://news.futunn.com/main/live",
      "title": "富途牛牛 - 快讯",
      "type": "feed",
      "url": "rsshub://futunn/live"
    }
  ]
}
```
