# Maldita.es - Latest Updates

## Coverage
`index-only`

## Route
- Namespace: `maldita`
- Namespace Name: `Maldita.es`
- Route Path: `/maldita/updates/:category?`
- Route Name: `Latest Updates`
- Example: `/maldita/updates/desinfo`
- URL: `maldita.es`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `canonnizq`
- Source Location: `updates.ts`
- Source Module: `_None_`

## Description
Categories: all | desinfo | prebunking | investigaciones | control-del-poder | policy

## Parameters
- `category`: Category to fetch


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
  - `maldita.es/:category/`
- `target`: `/updates/:category`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "Categories: all | desinfo | prebunking | investigaciones | control-del-poder | policy",
  "example": "/maldita/updates/desinfo",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "updates.ts",
  "maintainers": [
    "canonnizq"
  ],
  "name": "Latest Updates",
  "parameters": {
    "category": "Category to fetch"
  },
  "path": "/updates/:category?",
  "radar": [
    {
      "source": [
        "maldita.es/:category/"
      ],
      "target": "/updates/:category"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
