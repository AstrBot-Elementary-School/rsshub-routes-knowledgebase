# Futubull 富途牛牛 - 要闻

## Coverage
`index-only`

## Route
- Namespace: `futunn`
- Namespace Name: `Futubull 富途牛牛`
- Route Path: `/futunn/main`
- Route Name: `要闻`
- Example: `/futunn/main`
- URL: `news.futunn.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `Wsine, nczitzk, kennyfong19931`
- Source Location: `main.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `news.futunn.com/main`
  - `news.futunn.com/:lang/main`
- `target`: `/main`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/futunn/main",
  "features": {
    "supportRadar": true
  },
  "heat": 62,
  "location": "main.ts",
  "maintainers": [
    "Wsine",
    "nczitzk",
    "kennyfong19931"
  ],
  "name": "要闻",
  "path": [
    "/main",
    "/"
  ],
  "radar": [
    {
      "source": [
        "news.futunn.com/main",
        "news.futunn.com/:lang/main"
      ],
      "target": "/main"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "富途牛牛 - 要闻 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "61252688943239169",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://news.futunn.com/main",
      "title": "富途牛牛 - 要闻",
      "type": "feed",
      "url": "rsshub://futunn/main"
    }
  ]
}
```
